---
title: GetBytes()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์.
type: docs
weight: 53
url: /th/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระที่จะเข้ารหัส. |
| charIndex | int | ออฟเซตของอาร์เรย์ต้นทาง. |
| charCount | int | ความยาวของซับอาร์เรย์ต้นทาง. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | บัฟเฟอร์ไบต์ปลายทาง. |
| byteIndex | int | ออฟเซตของบัฟเฟอร์ปลายทาง. |
| flush | **bool** | ถ้าจริง จะทำความสะอาดสถานะของเอนโคเดอร์ภายในหลังจากการคำนวณ. |

### ค่าที่คืน

จำนวนไบต์ที่เขียน.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | อักขระที่จะเข้ารหัส. |
| charCount | int | ความยาวของอาร์เรย์ต้นทาง. |
| bytes | **uint8_t** * | บัฟเฟอร์ไบต์ปลายทาง. |
| byteCount | int | ขนาดของบัฟเฟอร์ปลายทาง. |
| flush | **bool** | ถ้าจริง จะทำความสะอาดสถานะของเอนโคเดอร์ภายในหลังจากการคำนวณ. |

### ค่าที่คืน

จำนวนไบต์ที่เขียน.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)