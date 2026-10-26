---
title: GetByteCount()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รับจำนวนอักขระที่จำเป็นสำหรับการเข้ารหัสบัฟเฟอร์อักขระ.
type: docs
weight: 235
url: /th/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) เมธอด


รับจำนวนอักขระที่จำเป็นสำหรับการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระ. |
| index | int | จุดเริ่มต้นของส่วนย่อย. |
| count | int | ขนาดส่วนย่อย. |

### ค่าที่ส่งกลับ

ขนาดบัฟเฟอร์ที่ต้องการ.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) เมธอด


รับจำนวนอักขระที่จำเป็นสำหรับการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | บัฟเฟอร์อักขระ. |
| index | int | จุดเริ่มต้นของส่วนย่อย. |
| count | int | ขนาดส่วนย่อย. |

### ค่าที่ส่งกลับ

ขนาดบัฟเฟอร์ที่ต้องการ.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) เมธอด


รับจำนวนอักขระที่จำเป็นสำหรับการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | บัฟเฟอร์อักขระ. |
| index | int | จุดเริ่มต้นของส่วนย่อย. |
| count | int | ขนาดส่วนย่อย. |

### ค่าที่ส่งกลับ

ขนาดบัฟเฟอร์ที่ต้องการ.

## Encoding::GetByteCount(const String\&) เมธอด


รับจำนวนอักขระที่จำเป็นสำหรับการเข้ารหัสสตริง.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเข้ารหัส. |

### ค่าที่ส่งกลับ

ขนาดบัฟเฟอร์ที่ต้องการ.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) เมธอด


รับจำนวนอักขระที่จำเป็นสำหรับการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระ. |

### ค่าที่ส่งกลับ

ขนาดบัฟเฟอร์ที่ต้องการ.

## Encoding::GetByteCount(const char_t *, int) เมธอด


รับจำนวนอักขระที่จำเป็นสำหรับการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | บัฟเฟอร์อักขระ. |
| count | int | [Buffer](../../../system/buffer/) ขนาด. |

### ค่าที่ส่งกลับ

ขนาดบัฟเฟอร์ที่ต้องการ.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Encoding](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)