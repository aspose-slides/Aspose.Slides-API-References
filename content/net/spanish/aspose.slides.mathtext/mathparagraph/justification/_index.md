---
title: Justification
second_title: Aspose.Sildes for .NET API Reference
description: Justificación de párrafo Valor predeterminado CentradoComoGrupo
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathparagraph/justification/
---

## MathParagraph.Justification property

Justificación de párrafo Valor predeterminado: CentradoComoGrupo

```csharp
public MathJustification Justification { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### Vea También

* enum [MathJustification](../../mathjustification)
* class [MathParagraph](../../mathparagraph)
* namespace [Aspose.Slides.MathText](../../mathparagraph)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->