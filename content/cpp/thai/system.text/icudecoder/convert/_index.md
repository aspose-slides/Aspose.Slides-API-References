---
title: Convert()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: แปลงไบต์เป็นตัวอักษร.
type: docs
weight: 66
url: /th/system.text/icudecoder/convert/
---
## ICUDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) เมธอด

แปลงไบต์เป็นตัวอักษร

```cpp
virtual void System::Text::ICUDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์สำหรับถอดรหัส. |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์ตัวอักษรปลายทาง. |
| charIndex | int | ออฟเซ็ตของอาเรย์ปลายทาง. |
| charCount | int | ขนาดของอาเรย์ปลายทาง. |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะของตัวถอดรหัสภายในหลังจากการคำนวณ. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรที่ใช้เก็บจำนวนไบต์ที่อ่าน. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรที่ใช้เก็บจำนวนตัวอักษรที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งค่าเป็นจริงหากบัฟเฟอร์อินพุตหมดแล้วและเป็นเท็จในกรณีอื่น. |

## ICUDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) เมธอด

แปลงไบต์เป็นตัวอักษร

```cpp
virtual void System::Text::ICUDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | ไบต์สำหรับถอดรหัส. |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | char_t * | บัฟเฟอร์ตัวอักษรปลายทาง. |
| charCount | int | ขนาดของอาเรย์ปลายทาง. |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะของตัวถอดรหัสภายในหลังจากการคำนวณ. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรที่ใช้เก็บจำนวนไบต์ที่อ่าน. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรที่ใช้เก็บจำนวนตัวอักษรที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งค่าเป็นจริงหากบัฟเฟอร์อินพุตหมดแล้วและเป็นเท็จในกรณีอื่น. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICUDecoder](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)