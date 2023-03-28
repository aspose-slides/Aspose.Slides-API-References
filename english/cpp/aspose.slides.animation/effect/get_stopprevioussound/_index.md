---
title: get_StopPreviousSound()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the animation effect stops the previous sound. Read bool.
type: docs
weight: 196
url: /cpp/aspose.slides.animation/effect/get_stopprevioussound/
---
## Effect::get_StopPreviousSound() method


This attribute specifies if the animation effect stops the previous sound. Read **bool**.

```cpp
bool Aspose::Slides::Animation::Effect::get_StopPreviousSound() override
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

* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)
