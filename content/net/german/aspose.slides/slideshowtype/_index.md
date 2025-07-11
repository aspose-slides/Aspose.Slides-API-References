---
title: SlideShowType
second_title: Aspose.Slide für .NET API-Referenz
description: Basiseinstellungen für die Diashow. Vorfahren repräsentieren Typen der Diashow PresentedBySpeaker../presentedbyspeaker Präsentiert von einem Sprecher Vollbild BrowsedByIndividual../browsedbyindividual Durch einen einzelnen Benutzer betrachtet Fenster BrowsedAtKiosk../browsedatkiosk In einem Kiosk betrachtet Vollbild
type: docs
weight: 10180
url: /de/aspose.slides/slideshowtype/
---

## SlideShowType-Klasse

Basiseinstellungen für die Diashow. Vorfahren repräsentieren Typen der Diashow: [`PresentedBySpeaker`](../presentedbyspeaker) Präsentiert von einem Sprecher (Vollbild) [`BrowsedByIndividual`](../browsedbyindividual) Durch einen einzelnen Benutzer betrachtet (Fenster) [`BrowsedAtKiosk`](../browsedatkiosk) In einem Kiosk betrachtet (Vollbild)

```csharp
public abstract class SlideShowType
```

### Beispiele

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

### Siehe auch

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->