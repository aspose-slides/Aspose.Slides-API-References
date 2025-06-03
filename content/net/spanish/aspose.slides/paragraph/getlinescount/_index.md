---
title: GetLinesCount
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtener el número de líneas en un párrafo.
type: docs
weight: 60
url: /es/aspose.slides/paragraph/getlinescount/
---

## Método Paragraph.GetLinesCount

Obtener el número de líneas en un párrafo.

```csharp
public int GetLinesCount()
```

### Valor de Retorno

Cantidad de líneas en un párrafo

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide sld = pres.Slides[0];
    IAutoShape ashp = sld.Shapes.AddAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
    IParagraph para = ashp.TextFrame.Paragraphs[0];
    IPortion portion = para.Portions[0];
    portion.Text = "Ejemplo de Aspose Paragraph GetLinesCount()";
    Console.WriteLine("Cantidad de Líneas = {0}", para.GetLinesCount());
}
```

### Véase También

* clase [Paragraph](../../paragraph)
* espacio de nombres [Aspose.Slides](../../paragraph)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->