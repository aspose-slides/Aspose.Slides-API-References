---
title: RemoveAt
second_title: Aspose.Sildes for .NET API Reference
description: Elimina un elemento en el índice especificado de la colección.
type: docs
weight: 110
url: /es/aspose.slides.mathtext/mathparagraph/removeat/
---

## MathParagraph.RemoveAt method

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

### Ver También

* class [MathParagraph](../../mathparagraph)
* namespace [Aspose.Slides.MathText](../../mathparagraph)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->