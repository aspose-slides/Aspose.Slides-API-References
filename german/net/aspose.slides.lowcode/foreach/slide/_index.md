---
title: Slide
second_title: Aspose.Slides für .NET-API-Referenz
description: Jeden iterierenSlideaspose.slides.lowcode/foreach/slide in demPresentationaspose.slides/presentation .
type: docs
weight: 60
url: /de/net/aspose.slides.lowcode/foreach/slide/
---
## ForEach.Slide method

Jeden iterieren`Slide` in dem[`Presentation`](../../../aspose.slides/presentation) .

```csharp
public static void Slide(Presentation pres, ForEachSlideCallback forEachSlide)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | Presentation | Präsentation zum Iterieren von Folien |
| forEachSlide | ForEachSlideCallback | Rückruf, der für jede Folie aufgerufen wird |

### Beispiele

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    ForEach.Slide(pres, (slide, index) =>
    {
        slide.Name = $"Slide #{index}";
    });
} 
```

### Siehe auch

* class [Presentation](../../../aspose.slides/presentation)
* delegate [ForEachSlideCallback](../../foreach.foreachslidecallback)
* class [ForEach](../../foreach)
* namensraum [Aspose.Slides.LowCode](../../foreach)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->