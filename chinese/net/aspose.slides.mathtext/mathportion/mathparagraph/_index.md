---
title: MathParagraph
second_title: Aspose.Slides for .NET API 参考
description: 数学段落
type: docs
weight: 20
url: /zh/net/aspose.slides.mathtext/mathportion/mathparagraph/
---
## MathPortion.MathParagraph property

数学段落

```csharp
public IMathParagraph MathParagraph { get; }
```

### 例子

示例:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAutoShape shape = pres.Slides[0].Shapes.AddMathShape(0, 0, 300, 50);
    IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
    mathParagraph.Add(new MathBlock(new MathematicalText("x+y")));
}
```

### 也可以看看

* interface [IMathParagraph](../../imathparagraph)
* class [MathPortion](../../mathportion)
* 命名空间 [Aspose.Slides.MathText](../../mathportion)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->