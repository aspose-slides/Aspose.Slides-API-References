---
title: IndexOf
second_title: Aspose.Slides for .NET API 参考
description: 确定集合中特定 IMathBlock 的索引
type: docs
weight: 80
url: /zh/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph.IndexOf method

确定集合中特定 IMathBlock 的索引。

```csharp
public int IndexOf(IMathBlock mathBlock)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | IMathBlock | 要在集合中定位的项目。 |

### 返回值

*mathBlock*的索引（如果在集合中找到）；否则，-1。

### 例子

示例:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
int index = mathParagraph.IndexOf(block);
```

### 也可以看看

* interface [IMathBlock](../../imathblock)
* class [MathParagraph](../../mathparagraph)
* 命名空间 [Aspose.Slides.MathText](../../mathparagraph)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
