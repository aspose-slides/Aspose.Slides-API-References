---
title: TrimStart()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัดองค์ประกอบที่ระบุออกจากจุดเริ่มต้นของสแปนที่มีประเภท
type: docs
weight: 391
url: /th/system.memoryextensions/trimstart/
---
## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน

ตัดองค์ประกอบที่ระบุออกจากจุดเริ่มต้นของสแปนที่มีประเภท

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const T &trimElement)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่จะทำการตัด |
| trimElement | const T\& | องค์ประกอบที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีองค์ประกอบที่ระบุถูกตัดออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const T\&) ฟังก์ชัน

ตัดองค์ประกอบที่ระบุออกจากจุดเริ่มต้นของสแปนที่เป็นแบบแก้ไขได้

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const T &trimElement)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ที่จะทำการตัด |
| trimElement | const T\& | องค์ประกอบที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีองค์ประกอบที่ระบุถูกตัดออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ตัดองค์ประกอบที่ระบุออกจากจุดเริ่มต้นของสแปนที่มีประเภท

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimStart(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่จะทำการตัด |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | องค์ประกอบที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีองค์ประกอบที่ระบุถูกตัดออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ตัดองค์ประกอบที่ระบุออกจากจุดเริ่มต้นของสแปนที่เป็นแบบแก้ไขได้

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimStart(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ที่จะทำการตัด |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | องค์ประกอบที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีองค์ประกอบที่ระบุถูกตัดออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระช่องว่างออกจากจุดเริ่มต้นของสแปนอักขระ

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนอักขระที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่ได้ตัดอักขระช่องว่างออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระช่องว่างออกจากจุดเริ่มต้นของสแปนอักขระที่สามารถแก้ไขได้

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | สแปนอักขระที่สามารถแก้ไขได้ที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่ได้ตัดอักขระช่องว่างออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, char16_t) ฟังก์ชัน

ตัดอักขระที่ระบุออกจากจุดเริ่มต้นของสแปนอักขระ

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนอักขระที่จะทำการตัด |
| trimchar | char16_t | อักขระที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่ได้ลบอักขระที่ระบุออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, char16_t) ฟังก์ชัน

ตัดอักขระที่ระบุออกจากจุดเริ่มต้นของสแปนอักขระที่สามารถแก้ไขได้

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, char16_t trimchar)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | สแปนอักขระที่สามารถแก้ไขได้ที่จะทำการตัด |
| trimchar | char16_t | อักขระที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่ได้ลบอักขระที่ระบุออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระที่ระบุออกจากจุดเริ่มต้นของสแปนอักขระ

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimStart(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนอักขระที่จะทำการตัด |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | อักขระที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่ได้ลบอักขระที่ระบุออกจากจุดเริ่มต้น

## System::MemoryExtensions::TrimStart(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระที่ระบุออกจากจุดเริ่มต้นของสแปนอักขระที่สามารถแก้ไขได้

```cpp
Span<char16_t> System::MemoryExtensions::TrimStart(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | สแปนอักขระที่สามารถแก้ไขได้ที่จะทำการตัด |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | อักขระที่จะทำการตัด |

### ค่าที่ส่งคืน

สแปนใหม่ที่ได้ลบอักขระที่ระบุออกจากจุดเริ่มต้น

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)