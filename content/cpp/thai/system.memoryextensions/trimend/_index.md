---
title: TrimEnd()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตัดองค์ประกอบที่ระบุออกจากส่วนท้ายของสแปนที่มีประเภทกำหนด.
type: docs
weight: 378
url: /th/system.memoryextensions/trimend/
---
## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน

ตัดองค์ประกอบที่ระบุออกจากส่วนท้ายของสแปนที่มีประเภทกำหนด

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const T &trimElement)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการตัด |
| trimElement | const T\& | องค์ประกอบที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดองค์ประกอบที่ระบุออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const T\&) ฟังก์ชัน

ตัดองค์ประกอบที่ระบุออกจากส่วนท้ายของสแปนที่สามารถแก้ไขได้

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const T &trimElement)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ที่ต้องการตัด |
| trimElement | const T\& | องค์ประกอบที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดองค์ประกอบที่ระบุออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ตัดองค์ประกอบหลายตัวที่ระบุออกจากส่วนท้ายของสแปนที่มีประเภทกำหนด

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการตัด |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | องค์ประกอบที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดองค์ประกอบที่ระบุออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ตัดองค์ประกอบหลายตัวที่ระบุออกจากส่วนท้ายของสแปนที่สามารถแก้ไขได้

```cpp
template<typename T> Span<T> System::MemoryExtensions::TrimEnd(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้ที่ต้องการตัด |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | องค์ประกอบที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดองค์ประกอบที่ระบุออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระช่องว่างออกจากส่วนท้ายของสแปนอักขระ

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนอักขระที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดช่องว่างออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระช่องว่างออกจากส่วนท้ายของสแปนอักขระที่สามารถแก้ไขได้

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | สแปนอักขระที่สามารถแก้ไขได้ที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดช่องว่างออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, char16_t) ฟังก์ชัน

ตัดอักขระที่ระบุออกจากส่วนท้ายของสแปนอักขระ

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, char16_t trimchar)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนอักขระที่ต้องการตัด |
| trimchar | char16_t | อักขระที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดอักขระที่ระบุออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, char16_t) ฟังก์ชัน

ตัดอักขระที่ระบุออกจากส่วนท้ายของสแปนอักขระที่สามารถแก้ไขได้

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, char16_t trimchar)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | สแปนอักขระที่สามารถแก้ไขได้ที่ต้องการตัด |
| trimchar | char16_t | อักขระที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดอักขระที่ระบุออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระหลายตัวที่ระบุออกจากส่วนท้ายของสแปนอักขระ

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::TrimEnd(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &trimChars)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนอักขระที่ต้องการตัด |
| trimChars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | อักขระที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดอักขระที่ระบุออกจากส่วนท้าย

## System::MemoryExtensions::TrimEnd(Span\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&) ฟังก์ชัน

ตัดอักขระหลายตัวที่ระบุออกจากส่วนท้ายของสแปนอักขระที่สามารถแก้ไขได้

```cpp
Span<char16_t> System::MemoryExtensions::TrimEnd(Span<char16_t> &span, const ReadOnlySpan<char16_t> &trimchars)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | สแปนอักขระที่สามารถแก้ไขได้ที่ต้องการตัด |
| trimchars | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | อักขระที่ต้องการตัด |

### ค่าที่ส่งกลับ

สแปนใหม่ที่ได้ตัดอักขระที่ระบุออกจากส่วนท้าย

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)