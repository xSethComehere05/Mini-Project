# PETra: Storytelling Dashboard อุตสาหกรรมพลาสติก

รายวิชา Business Idea Creation | PETra: เสื้อกัน UV/กันฝนจากขวด PET รีไซเคิล พร้อม AI Traceability

## สมาชิกกลุ่ม
ดู [docs/members.md](docs/members.md)

## Dashboard
เปิด `dashboard/index.html` ในเบราว์เซอร์ (ต้องต่ออินเทอร์เน็ตเพื่อโหลดฟอนต์และ Chart.js)
หรือเปิด GitHub Pages: Settings > Pages > Deploy from branch > folder `/dashboard`

## Data ที่ใช้
- ข้อมูลจำลองของบริษัท: `data/synthetic/` (อธิบายใน [docs/data_dictionary.md](docs/data_dictionary.md))
- แหล่งข้อมูลจริงที่ต้องใช้แทนค่าจำลองบทที่ 1-2: `data/raw/external_sources.csv`
- สร้างข้อมูลใหม่: `python scripts/generate_data.py`

## เนื้อเรื่อง
ดู [docs/story_board.md](docs/story_board.md)

## โครงสร้าง
```
data/raw  data/synthetic  scripts  dashboard  docs  screenshots
```
