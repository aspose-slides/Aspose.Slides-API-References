---
title: IndexOfAnyExceptInRange()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาดัชนีขององค์ประกอบแรกที่อยู่นอกช่วงที่ระบุใน ReadOnlySpan<T>
type: docs
weight: 183
url: /th/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบตัวแรกที่อยู่นอกช่วงที่ระบุใน ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสเปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | สเปนที่ต้องการค้นหา |
| lowInclusive | const T\& | ขอบล่างของช่วง (รวม) |
| highInclusive | const T\& | ขอบบนของช่วง (รวม) |

### ค่าที่คืนกลับ

ดัชนีเริ่มต้นที่ศูนย์ขององค์ประกอบตัวแรกที่อยู่นอกช่วง, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาดัชนีขององค์ประกอบตัวแรกที่อยู่นอกช่วงที่ระบุใน Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบในสเปน |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | สเปนที่ต้องการค้นหา |
| lowInclusive | const T\& | ขอบล่างของช่วง (รวม) |
| highInclusive | const T\& | ขอบบนของช่วง (รวม) |

### ค่าที่คืนกลับ

ดัชนีเริ่มต้นที่ศูนย์ขององค์ประกอบตัวแรกที่อยู่นอกช่วง, หรือ -1 หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมส페ซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)