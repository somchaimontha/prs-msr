# PRS-MSR

ระบบรายงานผลการปฏิบัติงานของวิทยาลัยการอาชีพแม่สะเรียง ใช้ Google Apps Script Web App ร่วมกับ Google Sheets และ Google Drive เป็นระบบหลัก

Repository สาธารณะนี้เก็บเฉพาะไฟล์อธิบายโครงการและตัวอย่างการตั้งค่าที่ไม่ใช่ความลับ ซอร์ส Apps Script, ชุดทดสอบ, เอกสารภายใน และไฟล์กำหนดค่าโครงการจริงถูกกันด้วย `.gitignore` ตามข้อกำหนดด้านข้อมูลอ่อนไหว จึงไม่ควรใช้ repository นี้เป็นสำเนาซอร์สครบชุด

การ deploy ใช้ `clasp` กับโปรเจกต์ Apps Script ที่ได้รับอนุญาต โดยไฟล์ตัวอย่าง `.clasp.json.example` ไม่มีรหัสโปรเจกต์จริง และ `.claspignore` ป้องกันไฟล์พัฒนา/ข้อมูลลับไม่ให้ถูกส่งไปพร้อมซอร์ส

ห้ามเพิ่ม PAT, OAuth token, Spreadsheet ID, Deployment ID, `.clasp.json`, `.clasprc.json` หรือข้อมูลส่วนบุคคลลงใน repository นี้
