---
title: SlideShowType
second_title: Aspose.Sildes for .NET API Reference
description: Base slide show settings. Ancestors represent types of the slide show PresentedBySpeaker./presentedbyspeaker Presented by a speaker full screen BrowsedByIndividual./browsedbyindividual Browsed by individual window BrowsedAtKiosk./browsedatkiosk Browsed at a kiosk full screen
type: docs
weight: 9730
url: /net/aspose.slides/slideshowtype/
---
## SlideShowType class

Base slide show settings. Ancestors represent types of the slide show: [`PresentedBySpeaker`](../presentedbyspeaker) Presented by a speaker (full screen) [`BrowsedByIndividual`](../browsedbyindividual) Browsed by individual (window) [`BrowsedAtKiosk`](../browsedatkiosk) Browsed at a kiosk (full screen)

```csharp
public abstract class SlideShowType
```

### Examples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    pres.SlideShowSettings.SlideShowType = new PresentedBySpeaker();
    pres.Save("PresentedBySpeaker.pptx", SaveFormat.Pptx);

    pres.SlideShowSettings.SlideShowType = new BrowsedByIndividual();
    pres.Save("BrowsedByIndividual.pptx", SaveFormat.Pptx);

    pres.SlideShowSettings.SlideShowType = new BrowsedAtKiosk();
    pres.Save("BrowsedAtKiosk.pptx", SaveFormat.Pptx);
}
```

### See Also

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->