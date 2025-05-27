---
title: ToLatex
second_title: Referencia de la API Aspose.Sildes para .NET
description: Obtiene ecuaciones matemáticas en formato LaTeX
type: docs
weight: 120
url: /es/aspose.slides.mathtext/mathparagraph/tolatex/
---

## Método MathParagraph.ToLatex

Obtiene ecuaciones matemáticas en formato LaTeX

```csharp
public string ToLatex()
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Add(new MathematicalText("a").Join("+").Join(new MathematicalText("b").Join("=").Join(new MathematicalText("c"))));
string mathLatex = mathParagraph.ToLatex();
```

### Véase también

* clase [MathParagraph](../../mathparagraph)
* espacio de nombres [Aspose.Slides.MathText](../../mathparagraph)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->