---
title: ImageType
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el tipo de imagen de un objeto de zoom. Lectura/escritura ZoomImageTypeaspose.slides/zoomimagetype. Valor por defecto Preview
type: docs
weight: 10
url: /es/aspose.slides/zoomobject/imagetype/
---

## Propiedad ZoomObject.ImageType

Obtiene o establece el tipo de imagen de un objeto de zoom. Lectura/escritura [`ZoomImageType`](../../zoomimagetype). Valor por defecto: Preview

```csharp
public ZoomImageType ImageType { get; set; }
```

### Comentarios

Especifica si el objeto de Zoom está utilizando la vista previa de la diapositiva o una imagen de portada.

### Ejemplos

El siguiente ejemplo demuestra cómo cambiar el tipo de imagen al valor Preview. En este caso, la imagen actual de un objeto de Zoom cambia a la imagen de la diapositiva:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1], image);
    zoomFrame.ImageType = ZoomImageType.Preview;
}
```

### Véase También

* enum [ZoomImageType](../../zoomimagetype)
* class [ZoomObject](../../zoomobject)
* namespace [Aspose.Slides](../../zoomobject)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->