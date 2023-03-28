---
title: set_Rewind()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the effect will rewind when done playing. Write bool.
type: docs
weight: 248
url: /cpp/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(**bool**) method


This attribute specifies if the effect will rewind when done playing. Write **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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

* Class [Timing](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
