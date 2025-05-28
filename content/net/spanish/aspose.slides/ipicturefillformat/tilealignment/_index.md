---
title: AlineaciónDeAzulejos
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de partida del patrón de textura y cómo se repite a lo largo de la forma. Lectura/escritura RectangleAlignmentaspose.slides/rectanglealignment.
type: docs
weight: 130
url: /es/aspose.slides/ipicturefillformat/tilealignment/
---

## Propiedad IPictureFillFormat.TileAlignment

Devuelve o establece cómo se alinea la textura dentro de la forma. Esta configuración controla el punto de partida del patrón de textura y cómo se repite a lo largo de la forma. Lectura/escritura [`RectangleAlignment`](../../rectanglealignment).

```csharp
public RectangleAlignment TileAlignment { get; set; }
```

### Observaciones

El valor predeterminado es ArribaIzquierda.

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Obtiene el formato de relleno de imagen de la forma
    IPictureFillFormat pictureFillFormat = slide.Shapes[0].FillFormat.PictureFillFormat;

    // Establece el modo de relleno de imagen a Azulejo
    pictureFillFormat.PictureFillMode = PictureFillMode.Tile;

    // Establece la alineación para el azulejado a la esquina inferior derecha
    pictureFillFormat.TileAlignment = RectangleAlignment.BottomRight;
}
```

### Véase También

* enum [RectangleAlignment](../../rectanglealignment)
* interface [IPictureFillFormat](../../ipicturefillformat)
* namespace [Aspose.Slides](../../ipicturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->