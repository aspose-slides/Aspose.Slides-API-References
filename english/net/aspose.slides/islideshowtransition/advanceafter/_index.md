---
title: AdvanceAfter
second_title: Aspose.Sildes for .NET API Reference
description: This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write Boolean.
type: docs
weight: 10
url: /net/aspose.slides/islideshowtransition/advanceafter/
---
## ISlideShowTransition.AdvanceAfter property

This attribute specifies if the slideshow will move to the next slide after a certain time. Read/write Boolean.

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    // Get the first slide Transition
    ISlideShowTransition slideTransition = pres.Slides[0].SlideShowTransition;
    
    // Check if the Advance Slide After flag is checked
    if (slideTransition.AdvanceAfter)
    {
        // Get the Advance Slide After Time value
        uint advanceAfterTime = slideTransition.AdvanceAfterTime;
    }
}
```

```csharp
public bool AdvanceAfter { get; set; }
```

### See Also

* interface [ISlideShowTransition](../../islideshowtransition)
* namespace [Aspose.Slides](../../islideshowtransition)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->