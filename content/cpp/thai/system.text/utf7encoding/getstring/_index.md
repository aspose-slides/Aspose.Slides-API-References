---
title: GetString()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.
type: docs
weight: 170
url: /th/system.text/utf7encoding/getstring/
---
## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
String System::Text::UTF7Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| count | int | ขนาดบัฟเฟอร์อินพุต. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(uint8_t *, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| byte_count | int | ขนาดบัฟเฟอร์อินพุต. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตリング.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| count | int | ขนาดบัฟเฟอร์อินพุต. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| count | int | ขนาดบัฟเฟอร์อินพุต. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## UTF7Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) เมธอด

ถอดรหัสบัฟเฟอร์ของไบต์เป็นสตริง.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) เพื่ออ่านไบต์จาก. |
| index | int | ออฟเซ็ตของบัฟเฟอร์อินพุต. |
| count | int | ขนาดบัฟเฟอร์อินพุต. |

### ค่าที่ส่งกลับ

[String](../../../system/string/) ของอักขระที่ถอดรหัส.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [String](../../../system/string/)
* คลาส [UTF7Encoding](../)
* คลาส [ReadOnlySpan](../../../system/readonlyspan/)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)