---
title: SequenceCompareTo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقارن بين اثنين من ReadOnlySpans ترتيبًا معجميًا.
type: docs
weight: 313
url: /ar/system.memoryextensions/sequencecompareto/
---
## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يقارن بين اثنين من ReadOnlySpan ترتيبًا معجميًا.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &other)
```

### معاملـات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span الأول للمقارنة |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ other الثاني للمقارنة |

### قيمة الإرجاع

- 1 إذا كان span < other، 0 إذا كان span == other، 1 إذا كان span > other

## System::MemoryExtensions::SequenceCompareTo(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) دالة

يقارن بين [Span](../../system/span/) و [ReadOnlySpan](../../system/readonlyspan/) ترتيبًا معجميًا.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const Span<T> &span, const ReadOnlySpan<T> &other)
```

### معاملـات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | الـ [Span](../../system/span/) للمقارنة |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ [ReadOnlySpan](../../system/readonlyspan/) للمقارنة |

### قيمة الإرجاع

- 1 إذا كان span < other، 0 إذا كان span == other، 1 إذا كان span > other

## System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan\<T\>\&, const Span\<T\>\&) دالة

يقارن بين [ReadOnlySpan](../../system/readonlyspan/) و [Span](../../system/span/) ترتيبًا معجميًا.

```cpp
template<typename T> int32_t System::MemoryExtensions::SequenceCompareTo(const ReadOnlySpan<T> &span, const Span<T> &other)
```

### معاملـات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ [ReadOnlySpan](../../system/readonlyspan/) للمقارنة |
| other | const [Span](../../system/span/)\<T\>\& | الـ [Span](../../system/span/) للمقارنة |

### قيمة الإرجاع

- 1 إذا كان span < other، 0 إذا كان span == other، 1 إذا كان span > other

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)