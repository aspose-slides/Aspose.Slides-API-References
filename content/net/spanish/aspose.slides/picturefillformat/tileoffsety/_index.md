---
title: TileOffsetY
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Lectura/escritura Single.
type: docs
weight: 150
url: /es/aspose.slides/picturefillformat/tileoffsety/
---

## Propiedad PictureFillFormat.TileOffsetY

Devuelve o establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia abajo, mientras que un valor negativo la mueve hacia arriba. Lectura/escritura Single.

```csharp
public float TileOffsetY { get; set; }
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

    // Establece el desplazamiento vertical de la textura a -50 puntos
    pictureFillFormat.TileOffsetY = -50;
}
```

### Véase también

* clase [PictureFillFormat](../../picturefillformat)
* espacio de nombres [Aspose.Slides](../../picturefillformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->