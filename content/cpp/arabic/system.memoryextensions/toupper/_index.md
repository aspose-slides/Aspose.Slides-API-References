---
title: ToUpper()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوِّل الأحرف إلى أحرف كبيرة باستخدام الثقافة المحددة.
type: docs
weight: 469
url: /ar/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) دالة

يحوِّل الأحرف إلى أحرف كبيرة باستخدام الثقافة المحددة.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | نطاق الأحرف المصدر للتحويل |
| destination | [Span](../../system/span/)\<char16_t\>\& | نطاق الوجهة لتخزين الأحرف المحوَّلة |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة للتحويل (nullptr للثقافة الحالية) |

### قيمة الإرجاع

عدد الأحرف المحوَّلة، أو -1 إذا كان حجم الوجهة صغيرًا جدًا

## انظر أيضًا

* Typedef [SharedPtr](../../system/sharedptr/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* فئة [CultureInfo](../../system.globalization/cultureinfo/)
* مساحة الاسم [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)