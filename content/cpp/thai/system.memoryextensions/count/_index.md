---
title: Count()
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: นับจำนวนการปรากฏของค่าภายใน ReadOnlySpan
type: docs
weight: 118
url: /th/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) ฟังก์ชัน

นับจำนวนการปรากฏของค่าใน ReadOnlySpan ที่เป็นแบบอ่านอย่างเดียว

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const T\& | The value to count |

### ค่าที่ส่งกลับ

จำนวนครั้งที่ค่าปรากฏใน span

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

นับจำนวนการปรากฏของ span ภายใน ReadOnlySpan อีกอันหนึ่ง

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to count occurrences of |

### ค่าที่ส่งกลับ

จำนวนครั้งที่ค่าปรากฏใน span

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) ฟังก์ชัน

นับจำนวนการปรากฏของค่าเดียวใน Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const T\& | The value to count occurrences of |

### ค่าที่ส่งกลับ

จำนวนการปรากฏของค่าใน span

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) ฟังก์ชัน

นับจำนวนการปรากฏของ ReadOnlySpan<T> ใน Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | The type of elements in the spans |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search in |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span containing values to count occurrences of |

### ค่าที่ส่งกลับ

จำนวนการปรากฏของ span ค่าใน span เป้าหมาย

## ดูเพิ่มเติม

* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)