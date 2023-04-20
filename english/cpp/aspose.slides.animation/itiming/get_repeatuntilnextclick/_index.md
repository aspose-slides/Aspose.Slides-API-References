---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the effect will repeat until the next click. Read bool.
type: docs
weight: 157
url: /cpp/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() method


This attribute specifies if the effect will repeat until the next click. Read **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
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

* Class [ITiming](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)