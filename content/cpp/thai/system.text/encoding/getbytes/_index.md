---
title: GetBytes()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ.
type: docs
weight: 248
url: /th/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระเพื่อเข้ารหัส |
| char_index | int | ตำแหน่งเริ่มต้นของส่วนอักขระ |
| char_count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระลง |
| byte_index | int | ออฟเซ็ตของบัฟเฟอร์ผลลัพธ์ |

### Return Value

จำนวนไบต์ที่เขียน

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | อักขระเพื่อเข้ารหัส |
| char_index | int | ตำแหน่งเริ่มต้นของส่วนอักขระ |
| char_count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระลง |
| byte_index | int | ออฟเซ็ตของบัฟเฟอร์ผลลัพธ์ |

### Return Value

จำนวนไบต์ที่เขียน

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | อักขระเพื่อเข้ารหัส |
| char_index | int | ตำแหน่งเริ่มต้นของส่วนอักขระ |
| char_count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) เพื่อใส่อักขระลง |
| byte_index | int | ออฟเซ็ตของบัฟเฟอร์ผลลัพธ์ |

### Return Value

จำนวนไบต์ที่เขียน

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเข้ารหัส |
| char_index | int | ตำแหน่งเริ่มต้นของส่วนอักขระ |
| char_count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระลง |
| byte_index | int | ออฟเซ็ตของบัฟเฟอร์ผลลัพธ์ |

### Return Value

จำนวนไบต์ที่เขียน

## Encoding::GetBytes(const String\&) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเข้ารหัส |

### Return Value

[Buffer](../../../system/buffer/) ที่เก็บการแทนค่าอักขระที่ถูกเข้ารหัส

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระเพื่อเข้ารหัส |
| index | int | ตำแหน่งเริ่มต้นของส่วนอักขระ |
| count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |

### Return Value

[Buffer](../../../system/buffer/) ที่เก็บการแทนค่าอักขระที่ถูกเข้ารหัส

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | อักขระเพื่อเข้ารหัส |
| index | int | ตำแหน่งเริ่มต้นของส่วนอักขระ |
| count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |

### Return Value

[Buffer](../../../system/buffer/) ที่เก็บการแทนค่าอักขระที่ถูกเข้ารหัส

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | อักขระเพื่อเข้ารหัส |
| index | int | ตำแหน่งเริ่มต้นของส่วนอักขระ |
| count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |

### Return Value

[Buffer](../../../system/buffer/) ที่เก็บการแทนค่าอักขระที่ถูกเข้ารหัส

## Encoding::GetBytes(ArrayPtr\<char_t\>) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | อักขระเพื่อเข้ารหัส |

### Return Value

[Buffer](../../../system/buffer/) ที่เก็บการแทนค่าอักขระที่ถูกเข้ารหัส

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) เมธอด


รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | อักขระเพื่อเข้ารหัส |
| char_count | int | จำนวนอักขระที่จะเปลี่ยนแปลง |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) เพื่อใส่อักขระลง |
| byte_count | int | ขนาดบัฟเฟอร์ผลลัพธ์ |

### Return Value

จำนวนไบต์ที่เขียน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Encoding](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)