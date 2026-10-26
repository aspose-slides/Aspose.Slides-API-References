---
title: CompareTo()
second_title: Aspose.Slides للغة C++ مرجع API
description: يقارن بين فترتين من الأحرف وفقًا لقواعد مقارنة السلاسل المحددة.
type: docs
weight: 404
url: /ar/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) دالة

يقارن بين فترتين من الأحرف وفقًا لقواعد مقارنة السلاسل المحددة.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | الفترة الأولى من الأحرف |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | الفترة الثانية من الأحرف |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقارنة السلاسل الذي سيتم تطبيقه |

### قيمة الإرجاع

قيمة سلبية إذا كان span < other، صفر إذا كانا متساويين، قيمة إيجابية إذا كان span > other

## أنظر أيضًا

* تعداد [StringComparison](../../system/stringcomparison/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* نطاق الاسم [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)