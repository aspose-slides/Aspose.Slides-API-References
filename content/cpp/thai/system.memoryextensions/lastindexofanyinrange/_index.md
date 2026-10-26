---
title: LastIndexOfAnyInRange()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ค้นหาการปรากฏครั้งสุดท้ายขององค์ประกอบใด ๆ ภายในช่วงที่ระบุใน span.
type: docs
weight: 261
url: /th/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายขององค์ประกอบใด ๆ ภายในช่วงที่ระบุใน span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | The type of elements in the span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### ค่าที่ส่งกลับ

The zero-based index of the last element within the range, or -1 if not found

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน

ค้นหาการปรากฏครั้งสุดท้ายขององค์ประกอบใด ๆ ภายในช่วงที่ระบุใน span ที่สามารถแก้ไขได้.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | The type of elements in the span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| lowInclusive | const T\& | The lower bound of the range (inclusive) |
| highInclusive | const T\& | The upper bound of the range (inclusive) |

### ค่าที่ส่งกลับ

The zero-based index of the last element within the range, or -1 if not found

## ดูเพิ่ม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)