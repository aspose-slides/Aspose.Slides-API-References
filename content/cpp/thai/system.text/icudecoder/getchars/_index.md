---
title: GetChars()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์
type: docs
weight: 53
url: /th/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์ที่ต้องถอดรหัส |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระปลายทาง |
| charIndex | int | ออฟเซ็ตของอาร์เรย์ปลายทาง |

### ค่าที่ส่งกลับ

จำนวนอักขระที่เขียน

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์ที่ต้องถอดรหัส |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระปลายทาง |
| charIndex | int | ออฟเซ็ตของอาร์เรย์ปลายทาง |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะของดีโคเดอร์ภายในหลังการคำนวณ |

### ค่าที่ส่งกลับ

จำนวนอักขระที่เขียน

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | const **uint8_t** * | ไบต์ที่ต้องถอดรหัส |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต |
| chars | char_t * | บัฟเฟอร์อักขระปลายทาง |
| charCount | int | ขนาดของอาร์เรย์ปลายทาง |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะของดีโคเดอร์ภายในหลังการคำนวณ |

### ค่าที่ส่งกลับ

จำนวนอักขระที่เขียน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICUDecoder](../)
* เนมสเปซ [System::Text](../../)
* Library [Aspose.Slides](../../../)