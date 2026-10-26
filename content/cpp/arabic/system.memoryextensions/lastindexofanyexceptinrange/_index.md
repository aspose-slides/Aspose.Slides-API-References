---
title: LastIndexOfAnyExceptInRange()
second_title: Aspose.Slides للغة C++ مرجع API
description: يبحث عن آخر ظهور لأي عنصر خارج النطاق المحدد داخل span.
type: docs
weight: 248
url: /ar/system.memoryextensions/lastindexofanyexceptinrange/
---
## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan\<T\>\&, const T\&, const T\&) دالة

يبحث عن آخر ظهور لأي عنصر خارج النطاق المحدد داخل span.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const ReadOnlySpan<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| T | نوع العناصر في span |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | span للبحث داخلها |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأقصى للنطاق (شامل) |

### قيمة الإرجاع

مؤشر العنصر الأخير خارج النطاق بدءًا من الصفر، أو -1 إذا لم يُعثر عليه

## System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span\<T\>\&, const T\&, const T\&) دالة

يبحث عن آخر ظهور لأي عنصر خارج النطاق المحدد داخل span قابل للتغيير.

```cpp
template<typename T> int32_t System::MemoryExtensions::LastIndexOfAnyExceptInRange(const Span<T> &span, const T &lowInclusive, const T &highInclusive)
```

### معلمات القالب

| معلمة | الوصف |
| --- | --- |
| T | نوع العناصر في span |

### الوسائط

| معلمة | النوع | الوصف |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | span للبحث داخلها |
| lowInclusive | const T\& | الحد الأدنى للنطاق (شامل) |
| highInclusive | const T\& | الحد الأقصى للنطاق (شامل) |

### قيمة الإرجاع

مؤشر العنصر الأخير خارج النطاق بدءًا من الصفر، أو -1 إذا لم يُعثر عليه

## انظر أيضًا

* الفئة [ReadOnlySpan](../../system/readonlyspan/)
* الفئة [Span](../../system/span/)
* مساحة الأسماء [System::MemoryExtensions](../)
* المكتبة [Aspose.Slides](../../)