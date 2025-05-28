---
title: RemoveAt
second_title: Referencia de API de Aspose.Slides para .NET
description: Elimina un elemento en el índice especificado de la colección.
type: docs
weight: 110
url: /es/aspose.slides.mathtext/mathparagraph/removeat/
---

## Método MathParagraph.RemoveAt

Elimina un elemento en el índice especificado de la colección.

```csharp
public void RemoveAt(int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero del elemento a eliminar. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
mathParagraph.RemoveAt(0);
```

### Véase también

* clase [MathParagraph](../../mathparagraph)
* espacio de nombres [Aspose.Slides.MathText](../../mathparagraph)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->