---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides لـ C++ مرجع API
description: تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى النقر التالي. قراءة bool.
type: docs
weight: 157
url: /ar/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() طريقة


هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. قراءة **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
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

* فئة [Timing](../)
* نطاق الاسم [Aspose::Slides::Animation](../../)
* مكتبة [Aspose.Slides](../../../)