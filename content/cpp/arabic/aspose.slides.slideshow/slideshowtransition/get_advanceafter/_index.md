---
title: get_AdvanceAfter()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: تحدد هذه الخاصية ما إذا كان عرض الشرائح سيتقدم إلى الشريحة التالية بعد وقت معين. قراءة bool.
type: docs
weight: 105
url: /ar/aspose.slides.slideshow/slideshowtransition/get_advanceafter/
---
## SlideShowTransition::get_AdvanceAfter() طريقة


تحدد هذه الخاصية ما إذا كان عرض الشرائح سيتقدم إلى الشريحة التالية بعد وقت معين. قراءة **bool**.

```cpp
bool Aspose::Slides::SlideShow::SlideShowTransition::get_AdvanceAfter() override
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// احصل على الانتقال الأول للشرائح
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// تحقق مما إذا تم تحديد علم الانتقال بعد الشريحة
if (slideTransition->get_AdvanceAfter())
{
    // احصل على قيمة وقت الانتقال بعد الشريحة
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## انظر أيضًا

* فئة [SlideShowTransition](../)
* مساحة الاسم [Aspose::Slides::SlideShow](../../)
* مكتبة [Aspose.Slides](../../../)