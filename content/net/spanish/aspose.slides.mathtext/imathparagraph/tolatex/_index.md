---
title: ToLatex
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene ecuación matemática en formato LaTeX
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathparagraph/tolatex/
---

## Método IMathParagraph.ToLatex

Obtiene ecuación matemática en formato LaTeX

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

* interfaz [IMathParagraph](../../imathparagraph)
* espacio de nombres [Aspose.Slides.MathText](../../imathparagraph)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->