---
title: TileOffsetX
second_title: Aspose.Slides para .NET Referencia de la API
description: Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha mientras que un valor negativo la mueve a la izquierda. Lectura/escritura Single.
type: docs
weight: 150
url: /es/aspose.slides/ipicturefillformat/tileoffsetx/
---

## Propiedad IPictureFillFormat.TileOffsetX

Devuelve o establece el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Lectura/escritura Single.

```csharp
public float TileOffsetX { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Obtiene el formato de relleno de imagen de la forma
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Establece el modo de relleno de imagen en Tile
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Establece el desplazamiento horizontal de la textura en 20 puntos
    pictureFillFormat.TileOffsetX = 20f;
}
```

### Véase también

* interfaz [IPictureFillFormat](../../ipicturefillformat)
* espacio de nombres [Aspose.Slides](../../ipicturefillformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->