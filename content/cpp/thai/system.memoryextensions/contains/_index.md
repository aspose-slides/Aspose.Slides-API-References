---
title: Contains()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าสแปนแบบอ่านอย่างเดียวมีค่าที่กำหนดหรือไม่.
type: docs
weight: 40
url: /th/system.memoryextensions/contains/
---
## System::MemoryExtensions::Contains(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน


ตรวจสอบว่าสตแปนแบบอ่านอย่างเดียวมีค่าที่กำหนดหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const ReadOnlySpan<T> &span, const T &value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สแปนที่ใช้ค้นหา |
| value | const T\& | ค่าที่ต้องการค้นหา |

### ค่าที่ส่งคืน

true หากพบค่าภายในสแปน, false หากไม่มี

## System::MemoryExtensions::Contains(const Span\<T\>\&, const T\&) ฟังก์ชัน


ตรวจสอบว่าสตแปนที่แก้ไขได้มีค่าที่กำหนดหรือไม่.

```cpp
template<typename T> bool System::MemoryExtensions::Contains(const Span<T> &span, const T &value)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของสมาชิกในสแปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สแปนที่แก้ไขได้ที่ใช้ค้นหา |
| value | const T\& | ค่าที่ต้องการค้นหา |

### ค่าที่ส่งคืน

true หากพบค่าภายในสแปน, false หากไม่มี

## System::MemoryExtensions::Contains(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) ฟังก์ชัน


ตรวจสอบว่าสแปนอักขระมีสแปนอักขระอื่นที่มีการเปรียบเทียบตามกฎที่ระบุหรือไม่.

```cpp
bool System::MemoryExtensions::Contains(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนที่ใช้ค้นหา |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | สแปนที่ต้องการค้นหา |
| comparisonType | [StringComparison](../../system/stringcomparison/) | ประเภทของการเปรียบเทียบสตริงที่ต้องทำ |

### ค่าที่ส่งคืน

true หากพบค่าภายในสแปน, false หากไม่มี

## ดูเพิ่มเติม

* Enum [StringComparison](../../system/stringcomparison/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)