---
title: set_InterruptionToken()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: الرمز لمراقبة طلبات الانقطاع.
type: docs
weight: 248
url: /ar/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) طريقة

الرمز لمراقبة طلبات الانقطاع.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## ملاحظات

يدير هذا الرمز كامل عمر مثال [IPresentation](../../ipresentation/). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض التقديمي، سيتم مقاطعتها عبر استدعاء طريقة [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) الخاصة بـ [IInterruptionTokenSource](../../iinterruptiontokensource/).

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IInterruptionToken](../../iinterruptiontoken/)
* فئة [ILoadOptions](../)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)