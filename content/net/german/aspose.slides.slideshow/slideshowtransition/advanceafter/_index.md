---
title: AdvanceAfter
second_title: Aspose.Slides für .NET API Referenz
description: Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lese-/Schreib-Boolean.
type: docs
weight: 10
url: /de/aspose.slides.slideshow/slideshowtransition/advanceafter/
---

## SlideShowTransition.AdvanceAfter-Eigenschaft

Dieses Attribut gibt an, ob die Diashow nach einer bestimmten Zeit zur nächsten Folie wechselt. Lese-/Schreib-Boolean.

```csharp
public bool AdvanceAfter { get; set; }
```

### Beispiele

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    // Holen Sie sich die Transition der ersten Folie
    ISlideShowTransition slideTransition = pres.Slides[0].SlideShowTransition;
    
    // Überprüfen, ob das Flag für das Voranschreiten der Folie aktiviert ist
    if (slideTransition.AdvanceAfter)
    {
        // Holen Sie sich den Wert für die Zeit nach der Folie
        uint advanceAfterTime = slideTransition.AdvanceAfterTime;
    }
}
```

### Siehe auch

* Klasse [SlideShowTransition](../../slideshowtransition)
* Namespace [Aspose.Slides.SlideShow](../../slideshowtransition)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->