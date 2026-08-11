---
title: set_AdvanceAfter()
second_title: مرجع API Aspose.Slides للغة C++
description: تحدد هذه الخاصية ما إذا كان عرض الشرائح سيتنقل إلى الشريحة التالية بعد زمن محدد. اكتب bool.
type: docs
weight: 118
url: /ar/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) طريقة


تحدد هذه الخاصية ما إذا كان العرض الشرائحي سيتنقل إلى الشريحة التالية بعد فترة زمنية محددة. اكتب **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// الحصول على الانتقال لأول شريحة
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// التحقق مما إذا كان علم التقدم إلى الشريحة التالية محددًا
if (slideTransition->get_AdvanceAfter())
{
    // الحصول على قيمة وقت التقدم إلى الشريحة التالية
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## انظر أيضًا

* فئة [ISlideShowTransition](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)