---
title: SequenceCompareTo()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบ ReadOnlySpans สองอันตามลำดับพจนานุกรม.
type: docs
weight: 313
url: /th/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

เปรียบเทียบ ReadOnlySpans สองอันตามลำดับพจนานุกรม.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span แรกเพื่อเปรียบเทียบ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่สองเพื่อเปรียบเทียบ |

### ค่าที่คืนกลับ

- 1 หาก span < other, 0 หาก span == other, 1 หาก span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

เปรียบเทียบ [Span](../../system/span/) และ [ReadOnlySpan](../../system/readonlyspan/) ตามลำดับพจนานุกรม.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) ที่จะเปรียบเทียบ |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) ที่จะเปรียบเทียบ |

### ค่าที่คืนกลับ

- 1 หาก span < other, 0 หาก span == other, 1 หาก span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) ฟังก์ชัน

เปรียบเทียบ [ReadOnlySpan](../../system/readonlyspan/) และ [Span](../../system/span/) ตามลำดับพจนานุกรม.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบใน span |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | [ReadOnlySpan](../../system/readonlyspan/) ที่จะเปรียบเทียบ |
| other | const [Span](../../system/span/)\<T\>\& | [Span](../../system/span/) ที่จะเปรียบเทียบ |

### ค่าที่คืนกลับ

- 1 หาก span < other, 0 หาก span == other, 1 หาก span > other

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)