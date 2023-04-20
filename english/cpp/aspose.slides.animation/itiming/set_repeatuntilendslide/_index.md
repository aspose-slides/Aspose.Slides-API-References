---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the effect will repeat until the end of the slide. Write bool.
type: docs
weight: 144
url: /cpp/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) method


This attribute specifies if the effect will repeat until the end of the slide. Write **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## See Also

* Class [ITiming](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)