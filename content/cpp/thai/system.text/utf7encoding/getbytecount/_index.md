---
title: GetByteCount()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับจำนวนอักขระที่ต้องใช้เพื่อเข้ารหัสบัฟเฟอร์อักขระ.
type: docs
weight: 157
url: /th/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) วิธีการ

รับจำนวนอักขระที่ต้องใช้ในการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | บัฟเฟอร์อักขระ. |
| count | int | [Buffer](../../../system/buffer/) ขนาด. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่จำเป็น.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) วิธีการ

รับจำนวนอักขระที่ต้องใช้ในการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระ. |
| index | int | จุดเริ่มต้นของส่วน. |
| count | int | ขนาดส่วน. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่จำเป็น.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) วิธีการ

รับจำนวนอักขระที่ต้องใช้ในการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | บัฟเฟอร์อักขระ. |
| index | int | จุดเริ่มต้นของส่วน. |
| count | int | ขนาดส่วน. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่จำเป็น.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) วิธีการ

รับจำนวนอักขระที่ต้องใช้ในการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | บัฟเฟอร์อักขระ. |
| index | int | จุดเริ่มต้นของส่วน. |
| count | int | ขนาดส่วน. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่จำเป็น.

## UTF7Encoding::GetByteCount(const String\&) วิธีการ

รับจำนวนอักขระที่ต้องใช้ในการเข้ารหัสสตริง.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) เพื่อเข้ารหัส. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่จำเป็น.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) วิธีการ

รับจำนวนอักขระที่ต้องใช้ในการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | บัฟเฟอร์อักขระ. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่จำเป็น.

## UTF7Encoding::GetByteCount(const char_t *, int) วิธีการ

รับจำนวนอักขระที่ต้องใช้ในการเข้ารหัสบัฟเฟอร์อักขระ.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | บัฟเฟอร์อักขระ. |
| count | int | [Buffer](../../../system/buffer/) ขนาด. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่จำเป็น.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [UTF7Encoding](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)