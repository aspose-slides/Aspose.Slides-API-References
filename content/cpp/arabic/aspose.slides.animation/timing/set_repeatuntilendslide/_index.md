---
title: set_RepeatUntilEndSlide()
second_title: مرجع API Aspose.Slides للغة C++
description: تحدد هذه السمة ما إذا كان التأثير سيُكرر حتى نهاية الشريحة. اكتب bool.
type: docs
weight: 144
url: /ar/aspose.slides.animation/timing/set_repeatuntilendslide/
---
## Timing::set_RepeatUntilEndSlide(bool) طريقة

This attribute specifies if the effect will repeat until the end of the slide. Write **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilEndSlide(bool value) override
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

* فئة [Timing](../)
* مساحة الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)