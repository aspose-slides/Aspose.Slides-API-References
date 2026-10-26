---
title: Convert()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงอักขระเป็นไบต์.
type: docs
weight: 66
url: /th/system.text/icuencoder/convert/
---
## ICUEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) เมธอด

แปลงอักขระเป็นไบต์.

```cpp
virtual void System::Text::ICUEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระที่จะเข้ารหัส |
| charIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| charCount | int | ขนาดของบัฟเฟอร์อินพุต |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ไบต์ปลายทาง |
| byteIndex | int | ออฟเซ็ตของอาเรย์ปลายทาง |
| byteCount | int | ขนาดของอาเรย์ปลายทาง |
| flush | **bool** | หากเป็นจริง จะทำการล้างสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ |
| charsUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนอักขระที่อ่าน |
| bytesUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนไบต์ที่เขียน |
| completed | **bool**\& | อ้างอิงไปยังตัวแปรที่ตั้งค่าเป็น true หากบัฟเฟอร์อินพุตถูกใช้จนหมดและเป็น false ในกรณีอื่น |

## ICUEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) เมธอด

แปลงอักขระเป็นไบต์.

```cpp
virtual void System::Text::ICUEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | อักขระที่จะเข้ารหัส |
| charCount | int | ขนาดของบัฟเฟอร์อินพุต |
| bytes | **uint8_t** * | บัฟเฟอร์ไบต์ปลายทาง |
| byteCount | int | ขนาดของอาเรย์ปลายทาง |
| flush | **bool** | หากเป็นจริง จะทำการล้างสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ |
| charsUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนอักขระที่อ่าน |
| bytesUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนไบต์ที่เขียน |
| completed | **bool**\& | อ้างอิงไปยังตัวแปรที่ตั้งค่าเป็น true หากบัฟเฟอร์อินพุตถูกใช้จนหมดและเป็น false ในกรณีอื่น |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICUEncoder](../)
* เนมสเปซ [System::Text](../../)
* Library [Aspose.Slides](../../../)