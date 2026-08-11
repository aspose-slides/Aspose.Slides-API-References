---
title: get_AdvanceAfter()
second_title: Aspose.Slides لـ C++ مرجع API
description: تحدد هذه السمة ما إذا كان عرض الشرائح سيتحرك إلى الشريحة التالية بعد وقت معين. اقرأ bool.
type: docs
weight: 105
url: /ar/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() طريقة

تحدد هذه السمة ما إذا كان عرض الشرائح سيتحرك إلى الشريحة التالية بعد وقت معين. اقرأ **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## ملاحظات



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// الحصول على أول انتقال شريحة
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// التحقق مما إذا كان علم Advance Slide After مفعّلاً
if (slideTransition->get_AdvanceAfter())
{
    // الحصول على قيمة زمن Advance Slide After
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## انظر أيضا

* فئة [ISlideShowTransition](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)