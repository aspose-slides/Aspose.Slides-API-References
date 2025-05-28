---
title: TileScaleX
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve o establece la escala horizontal para el relleno de textura como un porcentaje. Lectura/escritura Single.
type: docs
weight: 160
url: /es/aspose.slides/picturefillformat/tilescalex/
---

## Propiedad PictureFillFormat.TileScaleX

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

    // Obtiene el formato de relleno de imagen de la forma
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Establece el modo de relleno de imagen a Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Establece la escala horizontal para la textura al 120 por ciento
    pictureFillFormat.TileScaleX = 120;
}
```

### Véase También

* clase [PictureFillFormat](../../picturefillformat)
* espacio de nombres [Aspose.Slides](../../picturefillformat)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->