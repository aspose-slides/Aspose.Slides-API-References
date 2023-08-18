---
title: get_Rewind()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the effect will rewind when done playing. Read bool.
type: docs
weight: 313
url: /aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() method


This attribute specifies if the effect will rewind when done playing. Read **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## See Also

* Class [ITiming](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)