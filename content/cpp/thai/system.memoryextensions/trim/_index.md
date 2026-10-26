---
title: Trim()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ลบองค์ประกอบที่ระบุออกจากทั้งสองด้านของสแปนที่มีชนิดกำหนด.
type: docs
weight: 365
url: /th/system.memoryextensions/trim/
---
## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, T) ฟังก์ชัน

ลบองค์ประกอบที่ระบุออกจากทั้งสองด้านของสแปนที่มีชนิดกำหนด

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, T trimElement)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการลบ |
| trimElement | T | องค์ประกอบที่ต้องการลบ |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีองค์ประกอบที่ระบุถูกลบออกจากทั้งสองด้าน

## System::MemoryExtensions::Trim(Span\<T\>\&, T) ฟังก์ชัน

ลบองค์ประกอบที่ระบุออกจากทั้งสองด้านของสแปนที่มีชนิดที่สามารถแก้ไขได้

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, T trimElement)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้และต้องการลบ |
| trimElement | T | องค์ประกอบที่ต้องการลบ |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีองค์ประกอบที่ระบุถูกลบออกจากทั้งสองด้าน

## System::MemoryExtensions::Trim(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ลบหลายองค์ประกอบที่ระบุออกจากทั้งสองด้านของสแปนที่มีชนิดกำหนด

```cpp
template<typename T> ReadOnlySpan<T> System::MemoryExtensions::Trim(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &trimElements)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ต้องการลบ |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | หลายองค์ประกอบที่ต้องการลบ |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีหลายองค์ประกอบที่ระบุถูกลบออกจากทั้งสองด้าน

## System::MemoryExtensions::Trim(Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

ลบหลายองค์ประกอบที่ระบุออกจากทั้งสองด้านของสแปนที่มีชนิดที่สามารถแก้ไขได้

```cpp
template<typename T> Span<T> System::MemoryExtensions::Trim(Span<T> &span, const ReadOnlySpan<T> &trimElements)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | สแปนที่สามารถแก้ไขได้และต้องการลบ |
| trimElements | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | หลายองค์ประกอบที่ต้องการลบ |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีหลายองค์ประกอบที่ระบุถูกลบออกจากทั้งสองด้าน

## System::MemoryExtensions::Trim(const ReadOnlySpan\<char16_t\>\&) ฟังก์ชัน

ลบอักขระช่องว่างออกจากทั้งสองด้านของสแปนอักขระ

```cpp
ReadOnlySpan<char16_t> System::MemoryExtensions::Trim(const ReadOnlySpan<char16_t> &span)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนอักขระที่ต้องการลบ |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีช่องว่างถูกลบออกจากทั้งสองด้าน

## System::MemoryExtensions::Trim(Span\<char16_t\>\&) ฟังก์ชัน

ลบอักขระช่องว่างออกจากทั้งสองด้านของสแปนอักขระที่สามารถแก้ไขได้

```cpp
Span<char16_t> System::MemoryExtensions::Trim(Span<char16_t> &span)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | [Span](../../system/span/)\<char16_t\>\& | สแปนอักขระที่สามารถแก้ไขได้และต้องการลบ |

### ค่าที่ส่งคืน

สแปนใหม่ที่มีช่องว่างถูกลบออกจากทั้งสองด้าน

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)