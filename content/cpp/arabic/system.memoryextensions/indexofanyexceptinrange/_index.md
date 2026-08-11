---
title: IndexOfAnyExceptInRange()
second_title: مرجع API Aspose.Slides للغة C++
description: يجد الفهرس لأول عنصر يكون خارج النطاق المحدد في ReadOnlySpan<T>
type: docs
weight: 183
url: /ar/system.memoryextensions/indexofanyexceptinrange/
---
## System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) الدالة

يعثر على الفهرس لأول عنصر يكون خارج النطاق المحدد في ReadOnlySpan<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المقطع |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | المقطع المراد البحث فيه |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأعلى للنطاق (شامل) |

### قيمة الإرجاع

الفهرس صفر-أساسي لأول عنصر خارج النطاق، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::IndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) الدالة

يعثر على الفهرس لأول عنصر يكون خارج النطاق المحدد في Span<T>

```cpp
template<typename T> int32_t System::MemoryExtensions::IndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في المقطع |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | المقطع المراد البحث فيه |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأعلى للنطاق (شامل) |

### قيمة الإرجاع

الفهرس صفر-أساسي لأول عنصر خارج النطاق، أو -1 إذا لم يُعثر عليه

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)