---
title: TileScaleX
second_title: Aspose.Slides para .NET Referencia de la API
description: Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. Lectura/escritura Single.
type: docs
weight: 170
url: /es/aspose.slides/ipicturefillformat/tilescalex/
---

## IPictureFillFormat.TileScaleX propiedad

Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. Lectura/escritura Single.

```csharp
public float TileScaleX { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Obtiene el formato de relleno de la imagen de la forma
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Establece el modo de relleno de la imagen a Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Establece la escala horizontal para la textura a 120 por ciento
    pictureFillFormat.TileScaleX = 120;
}
```

### Ver También

* interface [IPictureFillFormat](../../ipicturefillformat)
* namespace [Aspose.Slides](../../ipicturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->