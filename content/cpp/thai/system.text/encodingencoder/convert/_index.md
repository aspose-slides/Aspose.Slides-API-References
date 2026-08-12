---
title: Convert()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงอักขระเป็นไบต์.
type: docs
weight: 1
url: /th/system.text/encodingencoder/convert/
---
## EncodingEncoder::Convert(const char_t *, int, uint8_t *, int, bool, int&, int&, bool&) method

แปลงอักขระเป็นไบต์

```cpp
virtual void System::Text::EncodingEncoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | อักขระที่ต้องเข้ารหัส. |
| charCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| bytes | **uint8_t** * | บัฟเฟอร์ไบต์ปลายทาง. |
| byteCount | int | ขนาดของอาร์เรย์ปลายทาง. |
| flush | **bool** | หากเป็น true จะล้างสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรที่เก็บจำนวนอักขระที่อ่าน. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรที่เก็บจำนวนไบต์ที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งค่าเป็น true หากบัฟเฟอร์อินพุตหมดและเป็น false ในกรณีอื่น. |

## EncodingEncoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

แปลงอักขระเป็นไบต์

```cpp
virtual void System::Text::EncodingEncoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระที่ต้องเข้ารหัส. |
| charIndex | int | การออฟเซ็ตของบัฟเฟอร์อินพุต. |
| charCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ไบต์ปลายทาง. |
| byteIndex | int | การออฟเซ็ตของอาร์เรย์ปลายทาง. |
| byteCount | int | ขนาดของอาร์เรย์ปลายทาง. |
| flush | **bool** | หากเป็น true จะล้างสถานะของตัวเข้ารหัสภายในหลังจากการคำนวณ. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรที่เก็บจำนวนอักขระที่อ่าน. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรที่เก็บจำนวนไบต์ที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งค่าเป็น true หากบัฟเฟอร์อินพุตหมดและเป็น false ในกรณีอื่น. |

## ดูเพิ่มเติม

* กำหนดประเภท [ArrayPtr](../../../system/arrayptr/)
* คลาส [EncodingEncoder](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)