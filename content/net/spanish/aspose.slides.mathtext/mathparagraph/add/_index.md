---
title: Agregar
second_title: Referencia de la API Aspose.Slides para .NET
description: Agrega IMathBlock al final de la colección.
type: docs
weight: 50
url: /es/aspose.slides.mathtext/mathparagraph/add/
---

## Método MathParagraph.Add

Agrega IMathBlock al final de la colección.

```csharp
public void Add(IMathBlock mathBlock)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathBlock | IMathBlock | Un bloque matemático que se añadirá al final de la colección |

### Ejemplos

Ejemplo:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Add(new MathBlock(new MathematicalText("x")));
```

### Ver También

* interfaz [IMathBlock](../../imathblock)
* clase [MathParagraph](../../mathparagraph)
* espacio de nombres [Aspose.Slides.MathText](../../mathparagraph)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->