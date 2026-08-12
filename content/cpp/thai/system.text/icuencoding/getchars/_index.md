---
title: GetChars()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์
type: docs
weight: 66
url: /th/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| byte_count | int | ขนาดบัฟเฟอร์อินพุต. |
| chars | char_t * | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ. |
| char_count | int | ขนาดบัฟเฟอร์เอาต์พุต. |

### ค่าที่คืนกลับ

จำนวนอักขระที่เขียน

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| byte_index | int | การชี้ตำแหน่งเริ่มต้นของบัฟเฟอร์อินพุต. |
| byte_count | int | ขนาดบัฟเฟอร์อินพุต. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ. |
| char_index | int | การชี้ตำแหน่งเริ่มต้นของบัฟเฟอร์เอาต์พุต. |

### ค่าที่คืนกลับ

จำนวนอักขระที่เขียน

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| index | int | การชี้ตำแหน่งเริ่มต้นของบัฟเฟอร์อินพุต. |
| count | int | ขนาดบัฟเฟอร์อินพุต. |

### ค่าที่คืนกลับ

[Buffer](../../../system/buffer/) ของอักขระที่ถอดรหัส

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |

### ค่าที่คืนกลับ

[Buffer](../../../system/buffer/) ของอักขระที่ถอดรหัส

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) เมธอด


รับอักขระที่ได้จากการถอดรหัสบัฟเฟอร์ไบต์

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| byte_count | int | ขนาดบัฟเฟอร์อินพุต. |
| chars | char_t * | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ. |
| char_count | int | ขนาดบัฟเฟอร์เอาต์พุต. |

### ค่าที่คืนกลับ

จำนวนอักขระที่เขียน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICUEncoding](../)
* เนมสเปซ [System::Text](../../)
* Library [Aspose.Slides](../../../)