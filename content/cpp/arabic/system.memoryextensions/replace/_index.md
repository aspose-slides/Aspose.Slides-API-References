---
title: Replace()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يستبدل جميع تكرارات قيمة بقيمة جديدة في Span.
type: docs
weight: 287
url: /ar/system.memoryextensions/replace/
---
## System::MemoryExtensions::Replace(Span\<T\>\&, const T\&, const T\&) دالة


يستبدل جميع حالات القيمة بقيمة جديدة في [Span](../../system/span/).

```cpp
template<typename T> void System::MemoryExtensions::Replace(Span<T> &span, const T &oldValue, const T &newValue)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | [Span](../../system/span/)\<T\>\& | الـ span لتعديله في الموضع |
| oldValue | const T\& | القيمة للبحث عنها واستبدالها |
| newValue | const T\& | القيمة الجديدة لاستبدال oldValue بها |

## System::MemoryExtensions::Replace(const ReadOnlySpan\<T\>\&, Span\<T\>\&, const T\&, const T\&) دالة


ينسخ العناصر من المصدر إلى الوجهة، مستبدلاً القيم المحددة أثناء النسخ.

```cpp
template<typename T> void System::MemoryExtensions::Replace(const ReadOnlySpan<T> &source, Span<T> &destination, const T &oldValue, const T &newValue)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ spans |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ source [ReadOnlySpan](../../system/readonlyspan/) للنسخ منه |
| destination | [Span](../../system/span/)\<T\>\& | الـ destination [Span](../../system/span/) للنسخ إليه |
| oldValue | const T\& | القيمة للبحث عنها واستبدالها أثناء النسخ |
| newValue | const T\& | القيمة الجديدة لاستبدال oldValue بها |

## انظر أيضًا

* الفئة [Span](../../system/span/)
* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* المساحة الاسمية [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)