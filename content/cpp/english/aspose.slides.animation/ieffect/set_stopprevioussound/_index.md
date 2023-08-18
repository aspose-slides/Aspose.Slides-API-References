---
title: set_StopPreviousSound()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the animation effect stops the previous sound. Write bool.
type: docs
weight: 209
url: /aspose.slides.animation/ieffect/set_stopprevioussound/
---
## IEffect::set_StopPreviousSound(bool) method


This attribute specifies if the animation effect stops the previous sound. Write **bool**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_StopPreviousSound(bool value)=0
```

## Remarks



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
auto firstSlideEffect = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence()->idx_get(0);

// Get the first effect of the second slide.
auto secondSlideEffect = presentation->get_Slides()->idx_get(1)->get_Timeline()->get_MainSequence()->idx_get(0);

if (firstSlideEffect->get_Sound() != nullptr)
{
    // Change the second effect Enhancements/Sound to "Stop Previous Sound"
    secondSlideEffect->set_StopPreviousSound(true);
}
```

## See Also

* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)