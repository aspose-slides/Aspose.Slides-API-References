---
title: GetByteCount()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับจำนวนอักขระที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์ตัวอักษร.
type: docs
weight: 27
url: /th/system.text/icuencoding/getbytecount/
---
## ICUEncoding::GetByteCount(const char_t *, int) เมธอด


รับจำนวนอักขระที่ต้องการเพื่อเข้ารหัสบัฟเฟอร์ตัวอักษร.

```cpp
int System::Text::ICUEncoding::GetByteCount(const char_t *chars, int count) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chars | const char_t * | บัฟเฟอร์ตัวอักษร. |
| count | int | [Buffer](../../../system/buffer/) ขนาด. |

### ค่าที่ส่งคืน

ขนาดบัฟเฟอร์ที่ต้องการ.

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>, int, int) เมธอด


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) เมธอด


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

## ICUEncoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) เมธอด


RTTI.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

## ICUEncoding::GetByteCount(const String\&) เมธอด


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

## ICUEncoding::GetByteCount(ArrayPtr\<char_t\>) เมธอด


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

## ICUEncoding::GetByteCount(const char_t *, int) เมธอด


RTTI.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

## ดูเพิ่มเติม

* ชนิดนิยาม [ArrayPtr](../../../system/arrayptr/)
* คลาส [ICUEncoding](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [System::Text](../../)
* ไลบรารี [Aspose.Slides](../../../)