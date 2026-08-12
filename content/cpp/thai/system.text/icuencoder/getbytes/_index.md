---
title: GetBytes()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ดึงไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์.
type: docs
weight: 53
url: /th/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) เมธอด

ดึงไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระที่จะเข้ารหัส |
| charIndex | int | ออฟเซ็ตของอาร์เรย์ต้นทาง |
| charCount | int | ความยาวของอาร์เรย์ย่อยต้นทาง |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ไบต์ปลายทาง |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์ปลายทาง |
| flush | **bool** | ถ้าเป็นจริง จะทำความสะอาดสถานะของเอ็นโคเดอร์ภายในหลังจากการคำนวณ |

### ค่าที่คืน

จำนวนไบต์ที่เขียน.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) เมธอด

ดึงไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | อักขระที่จะเข้ารหัส |
| charCount | int | ความยาวของอาร์เรย์ต้นทาง |
| bytes | **uint8_t** * | บัฟเฟอร์ไบต์ปลายทาง |
| byteCount | int | ขนาดของบัฟเฟอร์ปลายทาง |
| flush | **bool** | ถ้าเป็นจริง จะทำความสะอาดสถานะของเอ็นโคเดอร์ภายในหลังจากการคำนวณ |

### ค่าที่คืน

จำนวนไบต์ที่เขียน.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)