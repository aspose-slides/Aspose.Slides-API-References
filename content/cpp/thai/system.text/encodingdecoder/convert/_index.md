---
title: Convert()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แปลงไบต์เป็นอักขระ.
type: docs
weight: 1
url: /th/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) เมธอด

แปลงไบต์เป็นอักขระ.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const **uint8_t** * | ไบต์ที่ต้องถอดรหัส. |
| byteCount | int | ขนาดบัฟเฟอร์อินพุต. |
| chars | char_t * | บัฟเฟอร์อักขระปลายทาง. |
| charCount | int | ขนาดอาร์เรย์ปลายทาง. |
| flush | **bool** | หากเป็น true, ทำความสะอาดสถานะของดีโค้ดภายในหลังการคำนวณ. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนไบต์ที่อ่าน. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนอักขระที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งเป็น true หากบัฟเฟอร์อินพุตหมดและเป็น false ในกรณีอื่น. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) เมธอด

แปลงไบต์เป็นอักขระ.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์ที่ต้องถอดรหัส. |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| byteCount | int | ขนาดบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระปลายทาง. |
| charIndex | int | ออฟเซ็ตของอาร์เรย์ปลายทาง. |
| charCount | int | ขนาดอาร์เรย์ปลายทาง. |
| flush | **bool** | หากเป็น true, ทำความสะอาดสถานะของดีโค้ดภายในหลังการคำนวณ. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนไบต์ที่อ่าน. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนอักขระที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งเป็น true หากบัฟเฟอร์อินพุตหมดและเป็น false ในกรณีอื่น. |

## ดูเพิ่มเติม

* กำหนดชนิด [ArrayPtr](../../../system/arrayptr/)
* คลาส [EncodingDecoder](../)
* เนมส페ซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)