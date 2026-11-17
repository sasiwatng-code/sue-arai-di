# ซื้ออะไรดี

แอพจดรายการซื้อของในตลาด + ประมาณงบ ข้อมูลเก็บในเบราว์เซอร์ของเครื่อง (localStorage)

## ขึ้น GitHub Pages
1. สร้าง repository ใหม่บน GitHub (เช่นชื่อ `sue-arai-di`) แบบ Public
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html, manifest.webmanifest, sw.js, icon-*.png) ไปไว้ที่ root ของ repo
3. ไปที่ Settings → Pages → Source เลือก "Deploy from a branch" → Branch `main` / `(root)` → Save
4. รอ 1-2 นาที จะได้ลิงก์ `https://<ชื่อผู้ใช้>.github.io/sue-arai-di/`

## ติดตั้งบน Android
เปิดลิงก์ด้วย Chrome → เมนู ⋮ → "ติดตั้งแอป" (Install app) หรือ "เพิ่มลงในหน้าจอหลัก"

## หมายเหตุ
- ข้อมูลผูกกับลิงก์นั้น ถ้าเปลี่ยนชื่อ repo/ลิงก์ ข้อมูลเดิมจะไม่ตามไป
- ถ้าแก้ไฟล์แล้วหน้าจอไม่เปลี่ยน ให้เปลี่ยนเลขเวอร์ชัน `C` ใน sw.js (เช่น v2)
