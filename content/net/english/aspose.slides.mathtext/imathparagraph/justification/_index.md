---
title: Justification
second_title: Aspose.Sildes for .NET API Reference
description: Paragraph Justification Default value CenteredAsGroup
type: docs
weight: 20
url: /aspose.slides.mathtext/imathparagraph/justification/
---

## IMathParagraph.Justification property

Paragraph Justification Default value: CenteredAsGroup

```csharp
public MathJustification Justification { get; set; }
```

### Examples

Example:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### See Also

* enum [MathJustification](../../mathjustification)
* interface [IMathParagraph](../../imathparagraph)
* namespace [Aspose.Slides.MathText](../../imathparagraph)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
