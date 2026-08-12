---
title: Replace()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนที่ค่าที่พบทั้งหมดด้วยค่าตัวใหม่ใน Span.
type: docs
weight: 287
url: /th/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน


แทนที่ค่าทั้งหมดที่พบด้วยค่าตัวใหม่ใน [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### อาร์กิวเม้นต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | The span to modify in-place |
| oldValue | const T\& | The value to search for and replace |
| newValue | const T\& | The new value to replace oldValue with |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) ฟังก์ชัน


คัดลอกองค์ประกอบจากแหล่งที่มาถึงปลายทางโดยแทนที่ค่าที่ระบุระหว่างการคัดลอก.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### อาร์กิวเม้นต์

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The source [ReadOnlySpan](../../system/readonlyspan/) to copy from |
| destination | [Span](../../system/span/)\<T\>\& | The destination [Span](../../system/span/) to copy to |
| oldValue | const T\& | The value to search for and replace during copying |
| newValue | const T\& | The new value to replace oldValue with |

## ดูเพิ่มเติม

* คลาส [Span](../../system/span/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)