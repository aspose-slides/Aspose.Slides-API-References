---
title: Convert()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แปลงอักขระเป็นไบต์.
type: docs
weight: 79
url: /th/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) เมธอด

แปลงอักขระเป็นไบต์.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระสำหรับการเข้ารหัส. |
| charIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| charCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ไบต์ปลายทาง. |
| byteIndex | int | ออฟเซ็ตของอาเรย์ปลายทาง. |
| byteCount | int | ขนาดของอาเรย์ปลายทาง. |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะของเอ็นโค้ดภายในหลังจากการคำนวณ. |
| charsUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนอักขระที่อ่านได้. |
| bytesUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนไบต์ที่เขียนได้. |
| completed | **bool**\& | อ้างอิงไปยังตัวแปรที่จะตั้งค่าเป็นจริงหากบัฟเฟอร์อินพุตหมดและเป็นเท็จในกรณีอื่น. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) เมธอด

แปลงอักขระเป็นไบต์.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | อักขระสำหรับการเข้ารหัส. |
| charCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| bytes | **uint8_t** * | บัฟเฟอร์ไบต์ปลายทาง. |
| byteCount | int | ขนาดของอาเรย์ปลายทาง. |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะของเอ็นโค้ดภายในหลังจากการคำนวณ. |
| charsUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนอักขระที่อ่านได้. |
| bytesUsed | int\& | อ้างอิงไปยังตัวแปรเพื่อเก็บจำนวนไบต์ที่เขียนได้. |
| completed | **bool**\& | อ้างอิงไปยังตัวแปรที่จะตั้งค่าเป็นจริงหากบัฟเฟอร์อินพุตหมดและเป็นเท็จในกรณีอื่น. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Encoder](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)