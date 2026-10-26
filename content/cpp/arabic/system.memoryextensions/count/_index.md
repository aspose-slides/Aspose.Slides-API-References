---
title: Count()
second_title: مرجع API Aspose.Slides للغة C++
description: يعدّ مرات ظهور قيمة في نطاق للقراءة فقط.
type: docs
weight: 118
url: /ar/system.memoryextensions/count/
---
## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const T\&) دالة

يعدّ مرات ظهور قيمة في نطاق للقراءة فقط.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value | const T\& | القيمة للعد |

### قيمة الإرجاع

عدد مرات ظهور القيمة في النطاق

## System::MemoryExtensions::Count(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يعدّ مرات ظهور نطاق داخل نطاق آخر للقراءة فقط.

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث فيه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق لعد مرات ظهوره |

### قيمة الإرجاع

عدد مرات ظهور النطاق في النطاق

## System::MemoryExtensions::Count(const Span\<T\>\&, const T\&) دالة

يعدّ مرات ظهور قيمة واحدة في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const T &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاق |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| value | const T\& | القيمة لعد مرات ظهورها |

### قيمة الإرجاع

عدد مرات ظهور القيمة في النطاق

## System::MemoryExtensions::Count(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يعدّ مرات ظهور ReadOnlySpan<T> في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::Count(const Span<T> &span, const ReadOnlySpan<T> &value)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في النطاقات |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث فيه |
| value | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق الذي يحتوي على القيم لعد مرات ظهورها |

### قيمة الإرجاع

عدد مرات ظهور نطاق القيمة في النطاق الهدف

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* المجال [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)