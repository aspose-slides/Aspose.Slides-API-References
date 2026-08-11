---
title: LastIndexOfAnyInRange()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن آخر ظهور لأي عنصر داخل النطاق المحدد داخل span.
type: docs
weight: 261
url: /ar/system.memoryextensions/lastindexofanyinrange/
---
## System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يبحث عن آخر ظهور لأي عنصر داخل النطاق المحدد داخل span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في span |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | النطاق للبحث داخله |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأعلى للنطاق (شامل) |

### قيمة الإرجاع

الفهرس الصفري للعنصر الأخير داخل النطاق، أو -1 إذا لم يتم العثور عليه

## System::MemoryExtensions::LastIndexOfAnyInRange(const Span\<T\>\&, const T\&, const T\&) دالة

يبحث عن آخر ظهور لأي عنصر داخل النطاق المحدد داخل span قابل للتعديل.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| T | نوع العناصر في span |

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | النطاق للبحث داخله |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأعلى للنطاق (شامل) |

### قيمة الإرجاع

الفهرس الصفري للعنصر الأخير داخل النطاق، أو -1 إذا لم يتم العثور عليه

## انظر أيضًا

* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* نطاق الاسم [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)