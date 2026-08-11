---
title: ToLower()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقوم بتحويل الأحرف إلى أحرف صغيرة باستخدام الثقافة المحددة.
type: docs
weight: 443
url: /ar/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) دالة

يقوم بتحويل الأحرف إلى أحرف صغيرة باستخدام الثقافة المحددة.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | نطاق الأحرف المصدر للتحويل |
| destination | [Span](../../system/span/)\<char16_t\>\& | نطاق الوجهة لتخزين الأحرف المحوّلة |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | الثقافة المستخدمة للتحويل (nullptr للثقافة الحالية) |

### قيمة الإرجاع

عدد الأحرف التي تم تحويلها، أو -1 إذا كان حجم الوجهة صغيرًا جدًا

## انظر أيضًا

* تعريف نوع [SharedPtr](../../system/sharedptr/)
* فئة [ReadOnlySpan](../../system/readonlyspan/)
* فئة [Span](../../system/span/)
* فئة [CultureInfo](../../system.globalization/cultureinfo/)
* مساحة الاسم [System::MemoryExtensions](../)
* مكتبة [Aspose.Slides](../../)