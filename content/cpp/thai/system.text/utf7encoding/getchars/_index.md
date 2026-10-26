---
title: GetChars()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์.
type: docs
weight: 92
url: /th/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) เมธอด


รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบท์จาก. |
| byte_index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| byte_count | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) เพื่อใส่ตัวอักษรไปยัง. |
| char_index | int | ออฟเซ็ตของบัฟเฟอร์เอาต์พุต. |

### ค่าที่ส่งกลับ

จำนวนตัวอักษรที่เขียน.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) เมธอด


รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) เพื่ออ่านไบท์จาก. |
| byte_count | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | char_t * | [Buffer](../../../system/buffer/) เพื่อใส่ตัวอักษรไปยัง. |
| char_count | int | ขนาดของบัฟเฟอร์เอาต์พุต. |

### ค่าที่ส่งกลับ

จำนวนตัวอักษรที่เขียน.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) เมธอด


รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบท์จาก. |
| byte_index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| byte_count | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) เพื่อใส่ตัวอักษรไปยัง. |
| char_index | int | ออฟเซ็ตของบัฟเฟอร์เอาต์พุต. |

### ค่าที่ส่งกลับ

จำนวนตัวอักษรที่เขียน.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) เมธอด


รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบท์จาก. |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| count | int | ขนาดของบัฟเฟอร์อินพุต. |

### ค่าที่ส่งกลับ

[Buffer](../../../system/buffer/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) เมธอด


รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบท์จาก. |

### ค่าที่ส่งกลับ

[Buffer](../../../system/buffer/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) เมธอด


รับตัวอักษรที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) เพื่ออ่านไบท์จาก. |
| byte_count | int | ขนาดของบัฟเฟอร์อินพุต. |
| chars | char_t * | [Buffer](../../../system/buffer/) เพื่อใส่ตัวอักษรไปยัง. |
| char_count | int | ขนาดของบัฟเฟอร์เอาต์พุต. |

### ค่าที่ส่งกลับ

จำนวนตัวอักษรที่เขียน.

## ดูเพิ่มเติม

* ชนิดนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [UTF7Encoding](../)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)