---
title: ContainsAnyInRange()
second_title: Aspose.Slides لـ C++ مرجع API
description: يتحقق مما إذا كان الـ read-only span يحتوي على أي عنصر ضمن النطاق المحدد.
type: docs
weight: 92
url: /ar/system.memoryextensions/containsanyinrange/
---
## System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يتحقق مما إذا كان الـ read-only span يحتوي على أي عنصر داخل النطاق المحدد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span (يجب أن تكون قابلة للمقارنة) |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | الـ span للبحث فيه |
| lowInclusive | const T\& | الحد الأدنى (شامل) |
| highInclusive | const T\& | الحد الأعلى (شامل) |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر داخل النطاق، false خلاف ذلك

## System::MemoryExtensions::ContainsAnyInRange(const Span\<T\>\&, const T\&, const T\&) دالة

يتحقق مما إذا كان الـ mutable span يحتوي على أي عنصر داخل النطاق المحدد.

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في الـ span (يجب أن تكون قابلة للمقارنة) |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | الـ span القابل للتعديل للبحث فيه |
| lowInclusive | const T\& | الحد الأدنى (شامل) |
| highInclusive | const T\& | الحد الأعلى (شامل) |

### قيمة الإرجاع

true إذا تم العثور على أي عنصر داخل النطاق، false خلاف ذلك

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* النطاق [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)