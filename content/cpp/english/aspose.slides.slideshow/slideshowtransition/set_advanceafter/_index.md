---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API Reference
description: This attribute specifies if the slideshow will move to the next slide after a certain time. Write bool.
type: docs
weight: 118
url: /aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) method


This attribute specifies if the slideshow will move to the next slide after a certain time. Write **bool**.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
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

* Class [SlideShowTransition](../)
* Namespace [Aspose::Slides::SlideShow](../../)
* Library [Aspose.Slides](../../../)