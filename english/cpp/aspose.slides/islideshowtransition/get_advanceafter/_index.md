---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the slideshow will move to the next slide after a certain time. Read bool.
type: docs
weight: 105
url: /cpp/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() method


This attribute specifies if the slideshow will move to the next slide after a certain time. Read **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
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
