---
title: SplitTextByColumns
second_title: Referencia de API de Aspose.Slides para .NET
description: Divide el contenido de texto del ITextFrameaspose.slides/itextframe en un arreglo de cadenas donde cada elemento corresponde a una columna de texto separada dentro del marco.
type: docs
weight: 140
url: /es/aspose.slides/textframe/splittextbycolumns/
---

## Método TextFrame.SplitTextByColumns

Divide el contenido de texto del [`ITextFrame`](../../itextframe) en un arreglo de cadenas, donde cada elemento corresponde a una columna de texto separada dentro del marco.

```csharp
public string[] SplitTextByColumns()
```

### Valor de Retorno

Un arreglo de cadenas, donde cada cadena representa el contenido de texto de una columna específica en el [`ITextFrame`](../../itextframe).

### Comentarios

Si el marco de texto no contiene múltiples columnas, el arreglo devuelto tendrá un solo elemento que contiene el texto completo. Las columnas vacías se representarán como cadenas vacías en el arreglo.

### Ejemplos

El siguiente ejemplo demuestra cómo usar `SplitTextByColumns`:

```csharp
using (Presentation pres = new Presentation("example.pptx"))
{
    // Obtener la primera forma en la diapositiva y convertirla a ITextFrame
    ITextFrame textFrame = pres.Slides[0].Shapes[0] as ITextFrame;
    // Dividir el contenido del marco de texto en columnas
    string[] columnsText = textFrame.SplitTextByColumns();
    // Imprimir el texto de cada columna en la consola
    foreach (string column in columnsText)
        Console.WriteLine(column);
}
```

### Ver También

* clase [TextFrame](../../textframe)
* namespace [Aspose.Slides](../../textframe)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->