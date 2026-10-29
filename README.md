# MyBuy (PWA)

แอปจดรายจ่ายแบบกล่องฟิสิกส์ ติดตั้งบน iPhone ได้เหมือนแอปทั่วไป

## ติดตั้งบน iOS
1. อัปโหลดทุกไฟล์ในโฟลเดอร์นี้ขึ้นเว็บที่เป็น HTTPS (Netlify Drop, Cloudflare Pages, GitHub Pages หรือ Vercel ใช้ฟรี)
2. เปิดลิงก์ด้วย Safari บน iPhone
3. กดปุ่มแชร์ แล้วเลือก "เพิ่มไปยังหน้าจอโฮม" (Add to Home Screen)
4. เปิดจากไอคอน MyBuy ได้เลย ใช้แบบเต็มจอและใช้ออฟไลน์ได้หลังเปิดครั้งแรก

## หมายเหตุ
- ข้อมูลเก็บในเครื่อง (localStorage) แยกกันระหว่าง Safari กับแอปที่ติดตั้ง ใช้ Export สำรองไว้ก่อนย้ายได้
- ไฟล์: index.html, manifest.webmanifest, sw.js, icon-180/192/512.png
