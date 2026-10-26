---
title: IndexOfAnyInRange()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يجد الفهرس للعنصر الأول الذي يقع ضمن النطاق المحدد في ReadOnlySpan<T>
type: docs
weight: 196
url: /ar/system.memoryextensions/indexofanyinrange/
---
## System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يقوم بالعثور على فهرس العنصر الأول الذي يقع ضمن النطاق المحدد في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المدى للبحث فيه |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأعلى للنطاق (شامل) |

### قيمة الإرجاع

فهرس الصفري للعنصر الأول داخل النطاق، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::IndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) دالة

يقوم بالعثور على فهرس العنصر الأول الذي يقع ضمن النطاق المحدد في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المدى |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المدى للبحث فيه |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأعلى للنطاق (شامل) |

### قيمة الإرجاع

فهرس الصفري للعنصر الأول داخل النطاق، أو -1 إذا لم يتم العثور عليه

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* المجال [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)