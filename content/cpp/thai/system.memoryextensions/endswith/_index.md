---
title: EndsWith()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่า ReadOnlySpan<T> สิ้นสุดด้วยค่าหนึ่งหรือไม่
type: docs
weight: 131
url: /th/system.memoryextensions/endswith/
---
## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const T\&) function

ตรวจสอบว่า ReadOnlySpan<T> สิ้นสุดด้วยค่าหนึ่งหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const T &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดของสมาชิกใน span |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะตรวจสอบ |
| value | const T\& | ค่าที่จะตรวจสอบที่จุดสิ้นสุดของ span |

### ค่าที่ส่งคืน

true หาก span สิ้นสุดด้วยค่า, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

ตรวจสอบว่า ReadOnlySpan<T> สิ้นสุดด้วย ReadOnlySpan<T> อีกอันหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดของสมาชิกใน spans |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะตรวจสอบ |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะตรวจสอบที่จุดสิ้นสุดของ span เป้าหมาย |

### ค่าที่ส่งคืน

true หาก span สิ้นสุดด้วย span ค่า, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

ตรวจสอบว่า Span<T> สิ้นสุดด้วย ReadOnlySpan<T> หรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดของสมาชิกใน spans |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะตรวจสอบ |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะตรวจสอบที่จุดสิ้นสุดของ span เป้าหมาย |

### ค่าที่ส่งคืน

true หาก span สิ้นสุดด้วย span ค่า, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) function

ตรวจสอบว่า ReadOnlySpan<T> สิ้นสุดด้วย Span<T> หรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<T> &span, const Span<T> &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดของสมาชิกใน spans |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่จะตรวจสอบ |
| value | const [Span](../../system/span/)\<T\>\& | span ที่จะตรวจสอบที่จุดสิ้นสุดของ span เป้าหมาย |

### ค่าที่ส่งคืน

true หาก span สิ้นสุดด้วย span ค่า, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::EndsWith(const Span\<T\>\&, const Span\<T\>\&) function

ตรวจสอบว่า Span<T> สิ้นสุดด้วย Span<T> อีกอันหรือไม่

```cpp
template<typename T> bool System::MemoryExtensions::EndsWith(const Span<T> &span, const Span<T> &value)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | ชนิดของสมาชิกใน spans |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่จะตรวจสอบ |
| value | const [Span](../../system/span/)\<T\>\& | span ที่จะตรวจสอบที่จุดสิ้นสุดของ span เป้าหมาย |

### ค่าที่ส่งคืน

true หาก span สิ้นสุดด้วย span ค่า, false หากไม่เป็นเช่นนั้น

## System::MemoryExtensions::EndsWith(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

ตรวจสอบว่า ReadOnlySpan<char16_t> สิ้นสุดด้วยค่าที่ระบุโดยใช้ StringComparison หรือไม่

```cpp
bool System::MemoryExtensions::EndsWith(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span ที่จะตรวจสอบ |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ค่าที่จะตรวจสอบที่จุดสิ้นสุดของ span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | ประเภทการเปรียบเทียบสตริงที่ใช้ |

### ค่าที่ส่งคืน

true หาก span สิ้นสุดด้วยค่า, false หากไม่เป็นเช่นนั้น

## ดูเพิ่มเติม

* Enum [StringComparison](../../system/stringcomparison/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* ไลบรารี [Aspose.Slides](../../)