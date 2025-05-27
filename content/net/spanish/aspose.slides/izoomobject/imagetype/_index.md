---
title: ImageType
second_title: Aspose.Slides para Referencia de API de .NET
description: Obtiene o establece el tipo de imagen de un objeto de zoom. Lectura/escritura ZoomImageTypeaspose.slides/zoomimagetype. Valor predeterminado: Previsualización
type: docs
weight: 20
url: /es/aspose.slides/izoomobject/imagetype/
---

## Propiedad IZoomObject.ImageType

Obtiene o establece el tipo de imagen de un objeto de zoom. Lectura/escritura [`ZoomImageType`](../../zoomimagetype). Valor predeterminado: Previsualización

```csharp
public ZoomImageType ImageType { get; set; }
```

### Observaciones

Especifica si el objeto Zoom está utilizando la vista previa de la diapositiva o una imagen de portada.

### Ejemplos

Este ejemplo demuestra cómo cambiar el tipo de imagen al valor de Previsualización. En este caso, la imagen actual de un objeto Zoom cambia a la imagen de la diapositiva:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IPPImage image = pres.Images.AddImage(Image.FromFile("image.png"));
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1], image);
    zoomFrame.ImageType = ZoomImageType.Preview;
}
```

### Ver también

* enum [ZoomImageType](../../zoomimagetype)
* interface [IZoomObject](../../izoomobject)
* namespace [Aspose.Slides](../../izoomobject)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->