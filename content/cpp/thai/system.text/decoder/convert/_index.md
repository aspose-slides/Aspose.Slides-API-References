---
title: Convert()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แปลงไบต์เป็นอักขระ.
type: docs
weight: 79
url: /th/system.text/decoder/convert/
---
## Decoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) เมธอด

แปลงไบต์เป็นอักขระ.

```cpp
virtual void System::Text::Decoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์ที่ต้องถอดรหัส. |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระของปลายทาง. |
| charIndex | int | ออฟเซ็ตของอาร์เรย์ปลายทาง. |
| charCount | int | ขนาดของอาร์เรย์ปลายทาง. |
| flush | **bool** | หากเป็น true จะทำความสะอาดสถานะภายในของดีโคเดอร์หลังจากการคำนวน. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนไบต์ที่อ่านได้. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนอักขระที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งค่าเป็น true หากบัฟเฟอร์อินพุตหมดแล้วและเป็น false ในกรณีอื่น ๆ. |

## Decoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) เมธอด

แปลงไบต์เป็นอักขระ.

```cpp
virtual void System::Text::Decoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const **uint8_t** * | ไบต์ที่ต้องถอดรหัส. |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | char_t * | บัฟเฟอร์อักขระของปลายทาง. |
| charCount | int | ขนาดของอาร์เรย์ปลายทาง. |
| flush | **bool** | หากเป็น true จะทำความสะอาดสถานะภายในของดีโคเดอร์หลังจากการคำนวน. |
| bytesUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนไบต์ที่อ่านได้. |
| charsUsed | int\& | อ้างอิงถึงตัวแปรเพื่อเก็บจำนวนอักขระที่เขียน. |
| completed | **bool**\& | อ้างอิงถึงตัวแปรที่จะตั้งค่าเป็น true หากบัฟเฟอร์อินพุตหมดแล้วและเป็น false ในกรณีอื่น ๆ. |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Decoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)