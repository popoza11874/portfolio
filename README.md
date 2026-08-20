<img src="assets/header.svg" alt="Full-stack developer portfolio" width="100%" />

## <img src="assets/sticker-about.svg" width="34" align="center" alt="" /> About

ผมสนใจงานพัฒนาเว็บไซต์แบบ Full-stack และกำลังฝึกทำโปรเจกต์ที่ใช้งานได้จริง ตั้งแต่การออกแบบหน้าเว็บ เขียนระบบหลังบ้าน ไปจนถึงการจัดการฐานข้อมูล

ตอนนี้ใช้ **Next.js, TypeScript และ Supabase** เป็นหลัก และกำลังพัฒนาทักษะเรื่องโครงสร้างโปรเจกต์ การเขียน Component และ Authentication

---

## <img src="assets/sticker-work.svg" width="34" align="center" alt="" /> Selected work

<table>
  <tr>
    <td width="43%" valign="middle">
      <a href="https://github.com/popoza11874/bangkhen">
        <img src="https://raw.githubusercontent.com/popoza11874/bangkhen/main/public/ban-bang-khen.jpg" alt="Bangkhen website" width="100%" />
      </a>
    </td>
    <td width="57%" valign="middle">
      <h3>Bangkhen</h3>
      <p>เว็บไซต์แนะนำสถานที่ในเขตบางเขน พร้อมระบบ Admin สำหรับจัดการข้อมูล</p>
      <p><code>Next.js</code> <code>TypeScript</code> <code>Supabase</code></p>
      <a href="https://github.com/popoza11874/bangkhen"><strong>View project →</strong></a>
    </td>
  </tr>
</table>

### Project overview

Bangkhen เริ่มจากแนวคิดที่อยากรวบรวมข้อมูลสถานที่ในเขตบางเขนให้อยู่ในที่เดียว เพราะข้อมูลเดิมกระจายอยู่หลายแหล่งและค้นหาได้ไม่สะดวก เว็บไซต์จึงถูกออกแบบให้ผู้ใช้เปิดดูสถานที่ อ่านประวัติ ชมรูปภาพ และกดดูเส้นทางได้ง่ายทั้งบนคอมพิวเตอร์และโทรศัพท์มือถือ

### What I built

- หน้าแรกสำหรับแนะนำพื้นที่และสถานที่ที่น่าสนใจ
- หน้ารายละเอียดเฉพาะสำหรับวัด พิพิธภัณฑ์ สวน ร้านอาหาร และมหาวิทยาลัย
- หน้ารายละเอียดแบบ Dynamic ที่สร้างจาก `slug` และข้อมูลใน Supabase
- Gallery สำหรับแสดงภาพของแต่ละสถานที่
- Google Maps และปุ่มเปิดเส้นทางสำหรับผู้ใช้งาน
- ระบบ Login สำหรับผู้ดูแลด้วย Supabase Authentication
- ระบบเพิ่ม แก้ไข และลบข้อมูลสถานที่แบบ CRUD
- Dashboard สำหรับดูรายการล่าสุด คลังภาพ และกราฟสถิติ

### How it works

เว็บไซต์แบ่งออกเป็นสองส่วน ส่วนแรกเป็นหน้าสาธารณะสำหรับผู้เข้าชม โดยดึงข้อมูลสถานที่จากฐานข้อมูลมาแสดง ส่วนที่สองเป็นระบบ Admin ซึ่งจะตรวจสอบบัญชีและสิทธิ์ก่อนอนุญาตให้เข้าหน้าจัดการข้อมูล เมื่อผู้ดูแลเพิ่มสถานที่ใหม่ ระบบสามารถนำ `slug` ไปสร้าง URL ของหน้ารายละเอียดได้โดยไม่ต้องสร้างหน้าใหม่ทุกครั้ง

### My responsibilities

ผมพัฒนาทั้งส่วน Frontend และการเชื่อมต่อ Backend ตั้งแต่การแบ่งหน้าออกเป็น React Components การทำ Responsive Layout การเชื่อมต่อ Supabase ไปจนถึงการสร้างระบบ Authentication, CRUD และ Dashboard

### What I learned

- การจัดโครงสร้างโปรเจกต์ด้วย Next.js App Router
- การแยก Component เพื่อให้อ่านและแก้ไขโค้ดได้ง่ายขึ้น
- การออกแบบข้อมูลและเชื่อมต่อฐานข้อมูลผ่าน Supabase
- การตรวจสอบ Session และ Role ก่อนเข้าใช้งานหน้า Admin
- การจัดการ Loading, Error และสถานะที่ไม่พบข้อมูล
- การใช้ Git และ GitHub เพื่อติดตามการเปลี่ยนแปลงของโปรเจกต์

### Next improvements

- เพิ่มระบบค้นหาและกรองสถานที่ตามหมวดหมู่
- ปรับระบบอัปโหลดและจัดการรูปภาพให้สะดวกขึ้น
- เพิ่มการทดสอบส่วนสำคัญของระบบ
- ปรับปรุง Accessibility และประสิทธิภาพการโหลดหน้าเว็บ
- Deploy เว็บไซต์เพื่อเปิดเป็น Live Demo

---

## <img src="assets/sticker-stack.svg" width="40" align="center" alt="" /> Stack

```text
Frontend     Next.js / React / TypeScript / Tailwind CSS
Backend      Supabase / Authentication / CRUD
Tools        Git / GitHub / VS Code
```

## <img src="assets/sticker-contact.svg" width="38" align="center" alt="" /> Contact

GitHub — **[@popoza11874](https://github.com/popoza11874)**
