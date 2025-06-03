---
title: Insert
second_title: Referencia de la API de Aspose.Slides para .NET
description: Inserta IMathBlock en la colección en el índice especificado.
type: docs
weight: 90
url: /es/aspose.slides.mathtext/mathparagraph/insert/
---

## Método MathParagraph.Insert

Inserta IMathBlock en la colección en el índice especificado.

```csharp
public void Insert(int index, IMathBlock mathBlock)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | El índice basado en cero en el que se debe insertar un elemento. |
| mathBlock | IMathBlock | El IMathBlock a insertar. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Insert(0, block);
```

### Ver También

* interfaz [IMathBlock](../../imathblock)
* clase [MathParagraph](../../mathparagraph)
* espacio de nombres [Aspose.Slides.MathText](../../mathparagraph)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->