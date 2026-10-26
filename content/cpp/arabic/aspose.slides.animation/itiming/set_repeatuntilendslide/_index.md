---
title: set_RepeatUntilEndSlide()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: تحدد هذه الخاصية ما إذا كان التأثير سيُعاد حتى نهاية الشريحة. اكتب bool.
type: docs
weight: 144
url: /ar/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) طريقة


تحدد هذه الخاصية ما إذا كان التأثير سيُعاد حتى نهاية الشريحة. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## انظر أيضًا

* فئة [ITiming](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)