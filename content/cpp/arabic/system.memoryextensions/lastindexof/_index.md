---
title: LastIndexOf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن آخر تواجد لتسلسل داخل نطاق.
type: docs
weight: 209
url: /ar/system.memoryextensions/lastindexof/
---
## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

يبحث عن آخر تواجد لتسلسل داخل النطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### قيمة الإرجاع

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<T\>\&, const T\&) function

يبحث عن آخر تواجد لقيمة واحدة داخل النطاق.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<T> &span, const T &value)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### قيمة الإرجاع

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

يبحث عن آخر تواجد لتسلسل داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | The sequence to search for |

### قيمة الإرجاع

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const Span\<T\>\&, const T\&) function

يبحث عن آخر تواجد لقيمة واحدة داخل نطاق قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOf(const Span<T> &span, const T &value)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T | The type of elements in the span |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | The span to search within |
| value | const T\& | The value to search for |

### قيمة الإرجاع

The zero-based index of the last occurrence, or -1 if not found

## System::MemoryExtensions::LastIndexOf(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) function

يبحث عن آخر تواجد لقيمة داخل النطاق باستخدام مقارنة سلاسل محددة.

```cpp
int32_t System::MemoryExtensions::LastIndexOf(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &value, StringComparison comparisonType)
```

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The span to search within |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | The value to search for |
| comparisonType | [StringComparison](../../system/stringcomparison/) | The type of string comparison to perform |

### قيمة الإرجاع

The zero-based index of the last occurrence, or -1 if not found

## انظر أيضًا

* تعداد [StringComparison](../../system/stringcomparison/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* نطاق [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)