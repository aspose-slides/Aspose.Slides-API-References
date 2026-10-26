---
title: GetChars()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์.
type: docs
weight: 53
url: /th/system.text/decoder/getchars/
---
## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) เมธอด

รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์ที่ต้องถอดรหัส. |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระปลายทาง. |
| charIndex | int | ออฟเซ็ตของอาเรย์ปลายทาง. |

### ค่าที่ส่งคืน

จำนวนอักขระที่เขียน.

## Decoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) เมธอด

รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์.

```cpp
virtual int System::Text::Decoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ไบต์ที่ต้องถอดรหัส. |
| byteIndex | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระปลายทาง. |
| charIndex | int | ออฟเซ็ตของอาเรย์ปลายทาง. |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะภายในของดีโคดเดอร์หลังจากการคำนวณ. |

### ค่าที่ส่งคืน

จำนวนอักขระที่เขียน.

## Decoder::GetChars(const uint8_t *, int, char_t *, int, bool) เมธอด

รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์.

```cpp
virtual int System::Text::Decoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const **uint8_t** * | ไบต์ที่ต้องถอดรหัส. |
| byteCount | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | char_t * | บัฟเฟอร์อักขระปลายทาง. |
| charCount | int | ขนาดของอาเรย์ปลายทาง. |
| flush | **bool** | หากเป็นจริง จะทำความสะอาดสถานะภายในของดีโคดเดอร์หลังจากการคำนวณ. |

### ค่าที่ส่งคืน

จำนวนอักขระที่เขียน.

## ดูเพิ่มเติม

* ชนิดนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [Decoder](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)