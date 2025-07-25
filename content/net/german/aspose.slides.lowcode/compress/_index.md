---
title: Compress
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, Präsentationen zu komprimieren../aspose.slides/presentation.
type: docs
weight: 7630
url: /de/aspose.slides.lowcode/compress/
---

## Compress-Klasse

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, [`Presentation`](../../aspose.slides/presentation) zu komprimieren.

```csharp
public static class Compress
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [CompressEmbeddedFonts](../../aspose.slides.lowcode/compress/compressembeddedfonts)(Presentation) | Führt die Komprimierung der [`Presentation`](../../aspose.slides/presentation) durch, indem ungenutzte Zeichen aus eingebetteten Schriftarten entfernt werden. |
| static [RemoveUnusedLayoutSlides](../../aspose.slides.lowcode/compress/removeunusedlayoutslides)(Presentation) | Führt die Komprimierung der [`Presentation`](../../aspose.slides/presentation) durch, indem ungenutzte Layout-Folien entfernt werden. |
| static [RemoveUnusedMasterSlides](../../aspose.slides.lowcode/compress/removeunusedmasterslides)(Presentation) | Führt die Komprimierung der [`Presentation`](../../aspose.slides/presentation) durch, indem ungenutzte Master-Folien entfernt werden. |

### Beispiele

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    Aspose.Slides.LowCode.Compress.RemoveUnusedImages(pres);
    
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->