---
title: TileFlip
second_title: Referencia de API de Aspose.Slides para .NET
description: Voltea el tile de textura alrededor de su eje horizontal, vertical o ambos. Leer/escribir TileFlipaspose.slides/tileflip.
type: docs
weight: 140
url: /es/aspose.slides/ipicturefillformat/tileflip/
---

## Propiedad IPictureFillFormat.TileFlip

Voltea el tile de textura alrededor de su eje horizontal, vertical o ambos. Leer/escribir [`TileFlip`](../../tileflip).

```csharp
public TileFlip TileFlip { get; set; }
```

### Observaciones

El valor predeterminado es NoFlip.

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

    // Voltea el tile de textura alrededor de su eje vertical.
    pictureFillFormat.TileFlip = TileFlip.FlipY;
}
```

### Véase también

* enum [TileFlip](../../tileflip)
* interface [IPictureFillFormat](../../ipicturefillformat)
* namespace [Aspose.Slides](../../ipicturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->