---
title: ZoomImage
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece la imagen para el objeto de zoom. Leer/escribir IPPImageaspose.slides/ippimage.
type: docs
weight: 50
url: /es/aspose.slides/zoomobject/zoomimage/
---

## Propiedad ZoomObject.ZoomImage

Obtiene o establece la imagen para el objeto de zoom. Leer/escribir [`IPPImage`](../../ippimage).

```csharp
public IPPImage ZoomImage { get; set; }
```

### Ejemplos

El ejemplo demuestra cómo cambiar una imagen de un objeto de Zoom:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    zoomFrame.Image = image;
}
```

### Véase también

* interfaz [IPPImage](../../ippimage)
* clase [ZoomObject](../../zoomobject)
* espacio de nombres [Aspose.Slides](../../zoomobject)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->