---
title: Image
second_title: Aspose.Slides für .NET-API-Referenz
description: Holt oder setzt Bild für ZoomObjekt. Lesen/SchreibenIPPImageaspose.slides/ippimage .
type: docs
weight: 20
url: /de/aspose.slides/izoomobject/image/
---
## IZoomObject.Image property

Holt oder setzt Bild für Zoom-Objekt. Lesen/Schreiben[`IPPImage`](../../ippimage) .

```csharp
public IPPImage Image { get; set; }
```

### Beispiele

Das Beispiel zeigt das Ändern eines Bildes eines Zoom-Objekts:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    zoomFrame.Image = image;
}
```

### Siehe auch

* interface [IPPImage](../../ippimage)
* interface [IZoomObject](../../izoomobject)
* namensraum [Aspose.Slides](../../izoomobject)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
