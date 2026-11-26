# E-Porfolio

เว็บไซต์ Portfolio ส่วนตัวสำหรับแนะนำตัว ทักษะ ผลงาน และกิจกรรม สร้างด้วย HTML, CSS และ JavaScript โดยเน้นดีไซน์ที่เรียบง่าย รองรับการใช้งานบนอุปกรณ์หลายขนาด และนำทางภายในหน้าเว็บได้สะดวก

## รายละเอียดเว็บไซต์

- ส่วนหน้าแรกพร้อมข้อความแนะนำตัวและลิงก์ไปยัง GitHub
- ส่วนแนะนำตัวและรายชื่อทักษะ
- ส่วนแสดงผลงานที่น่าสนใจ
- ส่วนกิจกรรมและประสบการณ์แบบ Timeline
- เมนูนำทางแบบ Sticky และเมนูมือถือแบบเปิด-ปิด
- Highlight เมนูตามส่วนที่กำลังแสดงบนหน้าจอ
- แสดงปีปัจจุบันในส่วน Footer อัตโนมัติ
- ใช้ฟอนต์ Prompt จาก Google Fonts
- รองรับหน้าจอเดสก์ท็อป แท็บเล็ต และมือถือ
- รองรับการลด Motion สำหรับผู้ใช้ที่ตั้งค่าลดแอนิเมชัน

## เทคโนโลยีที่ใช้

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Intersection Observer API

## โครงสร้างไฟล์

```text
.
├── index.html
└── README.md
```

ไฟล์ `index.html` ประกอบด้วยโครงสร้างเนื้อหา รูปแบบการแสดงผล และ JavaScript ทั้งหมดอยู่ในไฟล์เดียว

## การใช้งาน

### เปิดในเครื่องของคุณ

1. โคลน repository

```bash
git clone https://github.com/tr32283-bot/e-porfolio.git
```

2. เข้าไปยังโฟลเดอร์โปรเจกต์

```bash
cd e-porfolio
```

3. เปิดไฟล์ `index.html` ด้วยเบราว์เซอร์ หรือเริ่มเซิร์ฟเวอร์แบบง่าย

```bash
python -m http.server 8000
```

4. เปิดเว็บไซต์ที่ `http://localhost:8000`

## การเผยแพร่ด้วย GitHub Pages

1. เปิด repository บน GitHub
2. ไปที่ **Settings** > **Pages**
3. ในส่วน **Build and deployment** เลือก:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
4. กด **Save**
5. รอให้ GitHub Pages สร้างเว็บไซต์ จากนั้นจะพบ URL ของเว็บไซต์ในหน้า Settings > Pages

## การปรับแต่ง

เนื้อหาและลิงก์ของ Portfolio ตั้งอยู่ในไฟล์ `index.html`

สามารถแก้ไขส่วนต่าง ๆ ได้ดังนี้:

- ข้อมูลส่วนตัวและทักษะในส่วน `<section class="about" id="about">`
- รายการผลงานใน `<div class="projects-grid">`
- กิจกรรมและประสบการณ์ใน `<div class="timeline">`
- สีหลักของเว็บไซต์ในตัวแปร CSS ภายใน `:root`
- โลโก้ประจำตัวใน `.profile-monogram` และ `.about-avatar`
- ลิงก์ GitHub และอีเมลในส่วน Contact

> ข้อมูลชื่อ เว็บไซต์อีเมล และรายการผลงานบางส่วนเป็นข้อมูลตัวอย่างควรปรับเป็นข้อมูลจริงก่อนเผยแพร่

## บทบาทผู้พัฒนา

- จัดวางโครงสร้างหน้าเว็บด้วย HTML
- ออกแบบหน้าตาและ Responsive Layout ด้วย CSS
- สร้างเมนูมือถือและ Active Navigation ด้วย JavaScript
- ใช้ Intersection Observer เพื่ออัปเดตเมนูตาม Section ที่กำลังแสดง

## ผู้จัดทำ

[tr32283-bot](https://github.com/tr32283-bot)

Repository: [https://github.com/tr32283-bot/e-porfolio](https://github.com/tr32283-bot/e-porfolio)

## License

ยังไม่ได้ระบุ License สำหรับโปรเจกต์นี้ หากต้องการอนุญาตให้ผู้อื่นนำโค้ดไปใช้งาน ควรเพิ่มไฟล์ License ที่เหมาะสม