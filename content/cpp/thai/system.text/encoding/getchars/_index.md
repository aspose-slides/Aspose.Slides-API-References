---
title: GetChars()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์
type: docs
weight: 274
url: /th/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |
| byte_index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| byte_count | int | ขนาดของบัฟเฟอร์อินพุต |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระลงไป |
| char_index | int | ออฟเซ็ตของบัฟเฟอร์เอาต์พุต |

### ค่าที่ส่งคืน

จำนวนอักขระที่เขียน

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| count | int | ขนาดของบัฟเฟอร์อินพุต |

### ค่าที่ส่งคืน

[Buffer](../../../system/buffer/) ของอักขระที่ถอดรหัส

## Encoding::GetChars(ArrayPtr\<uint8_t\>) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |

### ค่าที่ส่งคืน

[Buffer](../../../system/buffer/) ของอักขระที่ถอดรหัส

## Encoding::GetChars(const uint8_t *, int, char_t *, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### Arguments

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |
| byte_count | int | ขนาดของบัฟเฟอร์อินพุต |
| chars | char_t * | [Buffer](../../../system/buffer/) เพื่อใส่อักขระลงไป |
| char_count | int | ขนาดของบัฟเฟอร์เอาต์พุต |

### ค่าที่ส่งคืน

จำนวนอักขระที่เขียน

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Encoding](../)
* เนมสเปส [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)