---
title: ContainsAnyInRange()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: ตรวจสอบว่าช่วงที่อ่านอย่างเดียวมีองค์ประกอบใดในช่วงที่ระบุหรือไม่
type: docs
weight: 92
url: /th/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

ตรวจสอบว่า span แบบอ่านอย่างเดียวมีองค์ประกอบใดในช่วงที่ระบุหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span (ต้องสามารถเปรียบเทียบได้) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะค้นหา |
| lowInclusive | const T\& | ขอบล่าง (รวม) |
| highInclusive | const T\& | ขอบบน (รวม) |

### ค่าที่คืน

true หากพบองค์ประกอบใดในช่วง, false หากไม่พบ

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) function

ตรวจสอบว่า span ที่สามารถแก้ไขได้มีองค์ประกอบใดในช่วงที่ระบุหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span (ต้องสามารถเปรียบเทียบได้) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่สามารถแก้ไขได้เพื่อค้นหา |
| lowInclusive | const T\& | ขอบล่าง (รวม) |
| highInclusive | const T\& | ขอบบน (รวม) |

### ค่าที่คืน

true หากพบองค์ประกอบใดในช่วง, false หากไม่พบ

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)