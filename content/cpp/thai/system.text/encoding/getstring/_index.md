---
title: GetString()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.
type: docs
weight: 313
url: /th/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |
| byte_count | int | ขนาดบัฟเฟอร์อินพุต |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## Encoding::GetString(ArrayPtr\<uint8_t\>) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| count | int | ขนาดบัฟเฟอร์อินพุต |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตリング.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| count | int | ขนาดบัฟเฟอร์อินพุต |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต |
| count | int | ขนาดบัฟเฟอร์อินพุต |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [Encoding](../)
* คลาส [ReadOnlySpan](../../../system/readonlyspan/)
* เนมสเปซ [System::Text](../../)
* Library [Aspose.Slides](../../../)