---
title: ContainsAnyExceptInRange()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يتحقق مما إذا كان span للقراءة فقط يحتوي على أي عنصر خارج النطاق المحدد.
type: docs
weight: 79
url: /ar/system.memoryextensions/containsanyexceptinrange/
---
## System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يفحص ما إذا كان span للقراءة فقط يحتوي على أي عنصر خارج النطاق المحدد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span (يجب أن يكون قابلاً للمقارنة) |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span للبحث فيه |
| lowInclusive | const T\& | الحد الأدنى (شامل) |
| highInclusive | const T\& | الحد الأعلى (شامل) |

### قيمة الإرجاع

صحيح إذا تم العثور على أي عنصر خارج النطاق، خطأ خلاف ذلك

## System::MemoryExtensions::ContainsAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) دالة

يفحص ما إذا كان span قابل للتعديل يحتوي على أي عنصر خارج النطاق المحدد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span (يجب أن يكون قابلاً للمقارنة) |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | الـ span القابل للتعديل للبحث فيه |
| lowInclusive | const T\& | الحد الأدنى (شامل) |
| highInclusive | const T\& | الحد الأعلى (شامل) |

### قيمة الإرجاع

صحيح إذا تم العثور على أي عنصر خارج النطاق، خطأ خلاف ذلك

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)