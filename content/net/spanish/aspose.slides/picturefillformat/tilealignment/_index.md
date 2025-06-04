---
title: TileAlignment
second_title: Aspose.Sildes for .NET API Reference
description: Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a lo largo de la forma. Lectura/escritura RectangleAlignmentaspose.slides/rectanglealignment.
type: docs
weight: 120
url: /es/aspose.slides/picturefillformat/tilealignment/
---

## Propiedad PictureFillFormat.TileAlignment

Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de inicio del patrón de textura y cómo se repite a lo largo de la forma. Lectura/escritura [`RectangleAlignment`](../../rectanglealignment).

```csharp
public RectangleAlignment TileAlignment { get; set; }
```

### Comentarios

El valor predeterminado es SuperiorIzquierda.

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

    // Establece la alineación para el azulejo a la parte inferior derecha
    pictureFillFormat.TileAlignment = RectangleAlignment.BottomRight;
}
```

### Véase también

* enum [RectangleAlignment](../../rectanglealignment)
* class [PictureFillFormat](../../picturefillformat)
* namespace [Aspose.Slides](../../picturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->