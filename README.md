## CNC Library

> SPA practice assignment for React training @ CNC Lab

### Description

Web App สำหรับเก็บข้อมูลหนังสือที่มีอยู่ทั้งหมดใน CNC Lab

โดยหนังสือแต่ละเล่มจะมีข้อมูลดังนี้

- ชื่อหนังสือ
- Tag ที่เกี่ยวข้อง
- ปีที่พิมพ์
- ISBN

### Requirements

- สามารถแสดงรายการหนังสือทั้งหมด
- สามารถเพิ่ม/แก้ไข/ลบหนังสือได้
- สามารถค้นหาหนังสือได้ตามชื่อหนังสือ
- ให้เก็บข้อมูลหนังสือลงบน Local Web Storage ([ข้อมูลเพิ่มเติม](http://www.siamhtml.com/html5-web-storage/))
- กำหนด UI และ feature อื่น ๆ ตามชอบ

### ตัวอย่างข้อมูลหนังสือ

ชื่อหนังสือ | Tags | ปีที่พิมพ์ | ISBN
--- | --- | --- | ---
วิทยาการรหัสลับ | Computer Science, Crytography, Encryption, Security | 2010 | 978-616-90224-2-8
Clean Code | Software Engineering, Programming, Java, Design Pattern, Agile | 2009 | 978-0-13-235088-4

### Challenges (Optional)

- เพิ่มข้อมูลตำแหน่งของหนังสือ เช่น อยู่ตู้ที่ 3 ชั้นล่าง
- ค้นหาข้อมูลหนังสือตาม Tags/ปีที่พิมพ์/ISBN
- ตรวจสอบความถูกต้องของข้อมูลหนังสือก่อนเพิ่ม/แก้ไข
- ใส่รูปหนังสือได้
- เก็บข้อมูลลง Firebase Realtime Database หรือ Database อื่น ๆ
- มีระบบ Authentication ก่อนเข้าใช้ระบบ เช่น email/pass, Google, LINE
