---
title: ImageType
second_title: Aspose.Slides für .NET-API-Referenz
description: Holt oder setzt den Bildtyp eines ZoomObjekts. Lesen/SchreibenZoomImageTypeaspose.slides/zoomimagetype . Standardwert Vorschau
type: docs
weight: 30
url: /de/aspose.slides/izoomobject/imagetype/
---
## IZoomObject.ImageType property

Holt oder setzt den Bildtyp eines Zoom-Objekts. Lesen/Schreiben[`ZoomImageType`](../../zoomimagetype) . Standardwert: Vorschau

```csharp
public ZoomImageType ImageType { get; set; }
```

### Bemerkungen

Gibt an, ob das Zoom-Objekt die Folienvorschau oder ein Titelbild verwendet.

### Beispiele

Dieses Beispiel zeigt das Ändern des Bildtyps in den Vorschauwert. In diesem Fall ändert sich das aktuelle Bild eines Zoom-Objekts in das Dia-Bild:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1], image);
    zoomFrame.ImageType = ZoomImageType.Preview;
}
```

### Siehe auch

* enum [ZoomImageType](../../zoomimagetype)
* interface [IZoomObject](../../izoomobject)
* namensraum [Aspose.Slides](../../izoomobject)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
