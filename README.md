# Hack1
Import and Export (Sea food of Thailand)

# 🐟 Hack1 — การวิเคราะห์การนำเข้า-ส่งออกสินค้าประมงของประเทศไทย
> Import and Export Analysis of Thailand's Fishery Products

**ผู้จัดทำ:** ธวัช มหิทธิ (Tawat Mah) — รหัส 607745  
**อีเมล:** tawat.ma@gmail.com  
**GitHub:** [tawat-mah](https://github.com/tawat-mah)

---

## 📌 รายละเอียดโปรเจกต์

วิเคราะห์ข้อมูลการนำเข้าและส่งออกสินค้าประมงของประเทศไทย จำแนกตาม:
- 🌍 ประเทศคู่ค้า (Trading Partners)
- 📦 ประเภทสินค้า (HS Code)
- ⚖️ ปริมาณและน้ำหนักสินค้า
- 💰 มูลค่าการค้า
- 📅 เดือนและปีของการค้า (ปี 2568)

**แหล่งข้อมูล:** กรมศุลกากร ผ่าน THackle Platform (Dataset #93)  
**จำนวนข้อมูล:** 42,057 รายการ

---

## 📂 ไฟล์ในโปรเจกต์

| ไฟล์ | คำอธิบาย |
|---|---|
| `MiniHack_1_607745__ธวัช_มหิทธิ์.ipynb` | Jupyter Notebook หลัก (วิเคราะห์ข้อมูลทั้งหมด) |
| `MiniHack_EDA_Summary.html` | รายงาน EDA ในรูปแบบ HTML |
| `README.md` | ไฟล์นี้ |

---

## 🗂️ โครงสร้างการวิเคราะห์

| Section | หัวข้อ | สิ่งที่ได้ |
|---|---|---|
| Section 1 | Setup & Load Data | โหลดข้อมูล 42,057 รายการ ตรวจสอบโครงสร้าง |
| Section 2 | Exploratory Data Analysis (EDA) | 11 สมมติฐาน พบ Garbage 38% Missing 25 แถว |
| Section 3 | Data Quality & Cleaning | Clean เหลือ ~41,000 รายการ เพิ่ม Quarter/Season |
| Section 4 | Advanced Analysis | ตอบ 3 ข้อหลัก วิเคราะห์ Trading Partners/Product/Seasonal |
| Section 5 | Key Insights Summary | 10 Insights ยืนยัน 6 ข้อ New 2 ข้อ ระวัง 2 ข้อ |

---

## 🛠️ เครื่องมือที่ใช้

```
Python 3.10
pandas
numpy
matplotlib
seaborn
plotly
```

---

## 💡 Key Insights

- 🦐 ไทยพึ่งพาการนำเข้าวัตถุดิบกุ้งจากต่างประเทศสูง
- 🌏 มีการกระจุกตัวของคู่ค้าใน Top 5 ประเทศ
- 📈 สินค้าส่งออกหลักคืออาหารทะเลแปรรูป (กระป๋อง)
- 📅 มี Seasonal Pattern ที่ชัดเจนในบางช่วงเดือน

---

## 📋 ข้อเสนอแนะ

| รหัส | ความเร่งด่วน | หัวข้อ |
|---|---|---|
| R1 | 🔴 เร่งด่วน | เพิ่มข้อมูลย้อนหลัง 3-5 ปี เพื่อยืนยัน Seasonal Pattern |
| R2 | 🟡 ระยะกลาง | ลดพึ่งพา Import วัตถุดิบกุ้ง ลงทุนเพาะเลี้ยงในประเทศ |
| R3 | 🟡 ระยะกลาง | กระจายแหล่ง Import ลด Dependency จาก Top 5 ประเทศ |
| R4 | 🟢 ระยะยาว | พัฒนา Value Added Products ขยายจากกระป๋อง → อาหารแช่แข็งพรีเมียม |

---

## 🚀 วิธีรัน Notebook

1. เปิดไฟล์ใน [Google Colab](https://colab.research.google.com/)
2. Mount Google Drive และโหลดไฟล์ CSV
3. รัน Cell ตามลำดับจาก Section 1 ถึง Section 5

