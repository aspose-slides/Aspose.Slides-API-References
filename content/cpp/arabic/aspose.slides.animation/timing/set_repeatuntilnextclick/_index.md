---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: تحدد هذه الخاصية ما إذا كان التأثير سيتكرر حتى النقر التالي. اكتب bool.
type: docs
weight: 170
url: /ar/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) طريقة


هذه الخاصية تحدد ما إذا كان التأثير سيتكرر حتى النقر التالي. اكتب **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
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

* الفئة [Timing](../)
* المجال [Aspose::Slides::Animation](../../)
* المكتبة [Aspose.Slides](../../../)