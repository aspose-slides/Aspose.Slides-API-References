---
title: set_InterruptionToken()
second_title: مرجع API ل Aspose.Slides للغة C++
description: الرمز لمراقبة طلبات الإيقاف.
type: docs
weight: 248
url: /ar/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) طريقة

الرمز لمراقبة طلبات الإيقاف.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## ملاحظات

هذا الرمز يدير كامل عمر مثيل [IPresentation](../../ipresentation/). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض التقديمي، سيتم إيقافها عبر استدعاء طريقة [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) الخاصة بـ [InterruptionTokenSource](../../interruptiontokensource/).

## انظر أيضًا

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [IInterruptionToken](../../iinterruptiontoken/)
* فئة [LoadOptions](../)
* نطاق الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)