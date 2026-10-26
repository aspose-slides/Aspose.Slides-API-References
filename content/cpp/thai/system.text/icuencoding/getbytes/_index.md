---
title: GetBytes()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ
type: docs
weight: 40
url: /th/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ |
| byte_count | int | Output buffer size. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียน

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ |
| byte_index | int | Output buffer offset. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียน

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ |
| byte_index | int | Output buffer offset. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียน

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ |
| byte_index | int | Output buffer offset. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียน

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเข้ารหัส |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ |
| byte_index | int | Output buffer offset. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียน

## ICUEncoding::GetBytes(const String\&) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเข้ารหัส |

### ค่าที่ส่งกลับ

[Buffer](../../../system/buffer/) ที่ถือการแสดงผลของอักขระที่ถูกเข้ารหัส

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### ค่าที่ส่งกลับ

[Buffer](../../../system/buffer/) ที่ถือการแสดงผลของอักขระที่ถูกเข้ารหัส

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### ค่าที่ส่งกลับ

[Buffer](../../../system/buffer/) ที่ถือการแสดงผลของอักขระที่ถูกเข้ารหัส

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### ค่าที่ส่งกลับ

[Buffer](../../../system/buffer/) ที่ถือการแสดงผลของอักขระที่ถูกเข้ารหัส

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |

### ค่าที่ส่งกลับ

[Buffer](../../../system/buffer/) ที่ถือการแสดงผลของอักขระที่ถูกเข้ารหัส

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) เมธอด

รับไบต์ที่ได้จากการเข้ารหัสบัฟเฟอร์อักขระ

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) เพื่อใส่อักขระ |
| byte_count | int | Output buffer size. |

### ค่าที่ส่งกลับ

จำนวนไบต์ที่เขียน

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)