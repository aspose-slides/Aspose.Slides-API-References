---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the effect will repeat until the next click. Read bool.
type: docs
weight: 157
url: /cpp/aspose.slides.animation/timing/get_repeatuntilnextclick/
---
## Timing::get_RepeatUntilNextClick() method


This attribute specifies if the effect will repeat until the next click. Read **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilNextClick() override
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## See Also

* Class [Timing](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)