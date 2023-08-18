---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the slideshow will move to the next slide after a certain time. Write bool.
type: docs
weight: 118
url: /aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) method


This attribute specifies if the slideshow will move to the next slide after a certain time. Write **bool**.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// Get the first slide Transition
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Check if the Advance Slide After flag is checked
if (slideTransition->get_AdvanceAfter())
{
    // Get the Advance Slide After Time value
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## See Also

* Class [ISlideShowTransition](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)