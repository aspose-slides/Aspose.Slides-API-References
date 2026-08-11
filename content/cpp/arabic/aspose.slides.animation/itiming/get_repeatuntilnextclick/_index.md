---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides لـ C++ مرجع API
description: تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى النقر التالي. اقرأ bool.
type: docs
weight: 157
url: /ar/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() طريقة


تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى النقر التالي. اقرأ **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## ملاحظات


```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## انظر أيضًا

* فئة [ITiming](../)
* نطاق [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)