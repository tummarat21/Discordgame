# 🏮 สามก๊ก Discord Bot

บอทเกมสามก๊กภาษาไทยแบบครบวงจร พร้อมระบบขุนพล สงคราม และเศรษฐกิจในเซิร์ฟเวอร์ Discord

![ตัวอย่างเกม](https://i.imgur.com/XYzTkQS.png)

## ✨ คุณสมบัติหลัก
- เลือกขุนพลได้ 3 แบบ (โจโฉ, กวนอู, ขงเบ้ง)
- ระบบตลาดค้าขายระหว่างผู้เล่น
- สงคราม PvP และ PvE
- ระบบเมืองและทรัพยากร
- สนับสนุนภาษาไทยเต็มรูปแบบ

## 🛠️ วิธีติดตั้ง
### ข้อกำหนดเบื้องต้น
- Python 3.8+
- Discord Bot Token

### ขั้นตอนการติดตั้ง
```bash
# โคลนโปรเจกต์
git clone https://github.com/username/your-repo.git
cd your-repo

# ติดตั้ง dependencies
pip install -r requirements.txt

# ตั้งค่า Token
echo "DISCORD_TOKEN=your_token_here" > .env

# รันบอท
python main.py
