---
title: ToLatex
second_title: Aspose.Sildes for .NET API Reference
description: Obtiene ecuaciones matemáticas en formato LaTeX
type: docs
weight: 120
url: /es/aspose.slides.mathtext/mathparagraph/tolatex/
---

## MathParagraph.ToLatex método

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

### Ver También

* class [MathParagraph](../../mathparagraph)
* namespace [Aspose.Slides.MathText](../../mathparagraph)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->