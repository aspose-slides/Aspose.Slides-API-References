---
title: get_InterruptionToken()
second_title: مرجع API Aspose.Slides للغة C++
description: الرمز لمراقبة طلبات الإيقاف.
type: docs
weight: 235
url: /ar/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() طريقة

الرمز لمراقبة طلبات الإيقاف.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## ملاحظات

هذا الرمز يدير كامل دورة حياة مثيل [IPresentation](../../ipresentation/). أي عملية تستغرق وقتًا طويلاً، مثل التحميل أو الحفظ للعرض التقديمي، سيتم إيقافها عبر استدعاء طريقة [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) الخاصة بال[InterruptionTokenSource](../../interruptiontokensource/). 
## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IInterruptionToken](../../iinterruptiontoken/)
* فئة [LoadOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)