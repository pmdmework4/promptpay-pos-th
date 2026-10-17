# PromptPay POS Thailand

ระบบ POS สำหรับร้านค้า รองรับการขายสินค้า เงินสด และ PromptPay โดยมีแผนเชื่อมฐานข้อมูล Supabase เพื่อซิงก์ข้อมูลระหว่างอุปกรณ์

## สถานะ
กำลังพัฒนา — ยังไม่ใช่ระบบพร้อมใช้งานรับเงินจริง

## ความปลอดภัย
ไม่เก็บ Supabase service role key หรือรหัสผ่านใน GitHub; เก็บ secrets ใน Vercel Environment Variables เท่านั้น

## Deploy
เป้าหมายคือเชื่อม Repository นี้กับโปรเจกต์ Vercel `promptpay-pos-th` และทดสอบก่อนขึ้น Production
