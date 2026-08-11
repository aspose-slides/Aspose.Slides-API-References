---
title: get_RepeatUntilEndSlide()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. اقرأ bool.
type: docs
weight: 131
url: /ar/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() طريقة


تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى نهاية الشريحة. اقرأ **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
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

* الفئة [Timing](../)
* النطاق [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)