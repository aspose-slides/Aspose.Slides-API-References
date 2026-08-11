---
title: get_InterruptionToken()
second_title: مرجع API Aspose.Slides للغة C++
description: الرمز لمراقبة طلبات الانقطاع.
type: docs
weight: 235
url: /ar/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() طريقة

الرمز لمراقبة طلبات الانقطاع.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## ملاحظات

هذا الرمز يدير كامل عمر المثيل [IPresentation](../../ipresentation/). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض التقديمي، سيتم قطعها عبر استدعاء طريقة [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) لل[IInterruptionTokenSource](../../iinterruptiontokensource/).

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IInterruptionToken](../../iinterruptiontoken/)
* فئة [ILoadOptions](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)