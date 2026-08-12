---
title: IndexOf()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ค้นหาดัชนีของค่า ReadOnlySpan<T> ใน ReadOnlySpan<T> อีกอันหนึ่ง
type: docs
weight: 144
url: /th/system.memoryextensions/indexof/
---
## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

ค้นหาดัชนีของค่า ReadOnlySpan<T> ใน ReadOnlySpan<T> อีกอันหนึ่ง

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่ใช้ค้นหา |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่ต้องการค้นหา |

### Return Value

ดัชนีศูนย์ฐานของการเกิดครั้งแรก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

ค้นหาดัชนีของค่าหนึ่งค่าใน ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่ใช้ค้นหา |
| value | const T\& | ค่า ที่ต้องการค้นหา |

### Return Value

ดัชนีศูนย์ฐานของการเกิดครั้งแรก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

ค้นหาดัชนีของค่า ReadOnlySpan<T> ใน Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่ใช้ค้นหา |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span ที่ต้องการค้นหา |

### Return Value

ดัชนีศูนย์ฐานของการเกิดครั้งแรก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOf(const Span\<T\>\&, const T\&) function

ค้นหาดัชนีของค่าหนึ่งค่าใน Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOf(const Span<T> &span, const T &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | ชนิดขององค์ประกอบใน span |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span ที่ใช้ค้นหา |
| value | const T\& | ค่า ที่ต้องการค้นหา |

### Return Value

ดัชนีศูนย์ฐานของการเกิดครั้งแรก, หรือ -1 หากไม่พบ

## System::MemoryExtensions::IndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

ค้นหาดัชนีของค่า ReadOnlySpan<char16_t> ใน ReadOnlySpan<char16_t> ด้วย StringComparison.

```cpp
int32_t System::MemoryExtensions::IndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | span ที่ใช้ค้นหา |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | ค่า ที่ต้องการค้นหา |
| comparisonType | [StringComparison](../../system/stringcomparison/) | ประเภทการเปรียบเทียบสตริงที่ใช้ |

### Return Value

ดัชนีศูนย์ฐานของการเกิดครั้งแรก, หรือ -1 หากไม่พบ

## See Also

* Enum [StringComparison](../../system/stringcomparison/)
* คลาส [ReadOnlySpan](../../system/readonlyspan/)
* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions](../)
* Library [Aspose.Slides](../../)