---
title: Item
second_title: Aspose.Slides para .NET API Referencia
description: Obtiene el elemento en el índice especificado. Solo lectura IMathBlockaspose.slides.mathtext/imathblock.
type: docs
weight: 30
url: /es/aspose.slides.mathtext/mathparagraph/item/
---

## MathParagraph indexer

Obtiene el elemento en el índice especificado. Solo lectura [`IMathBlock`](../../imathblock).

```csharp
public IMathBlock this[int index] { get; set; }
```

| Parámetro | Descripción |
| --- | --- |
| index | El índice basado en cero del elemento a obtener |

### Valor de Retorno

El bloque de un texto matemático.

### Ejemplos

Ejemplo:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Add(new MathBlock(new MathematicalText("block1")));
mathParagraph.Add(new MathBlock(new MathematicalText("block2")));
IMathBlock block = mathParagraph[1];
```

### Véase También

* interfaz [IMathBlock](../../imathblock)
* clase [MathParagraph](../../mathparagraph)
* espacio de nombres [Aspose.Slides.MathText](../../mathparagraph)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->