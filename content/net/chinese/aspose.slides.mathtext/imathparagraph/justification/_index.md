---
title: Justification
second_title: Aspose.Slides for .NET API 参考
description: 段落对齐 默认值CenteredAsGroup
type: docs
weight: 20
url: /zh/aspose.slides.mathtext/imathparagraph/justification/
---
## IMathParagraph.Justification property

段落对齐 默认值:CenteredAsGroup

```csharp
public MathJustification Justification { get; set; }
```

### 例子

示例:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### 也可以看看

* enum [MathJustification](../../mathjustification)
* interface [IMathParagraph](../../imathparagraph)
* 命名空间 [Aspose.Slides.MathText](../../imathparagraph)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
