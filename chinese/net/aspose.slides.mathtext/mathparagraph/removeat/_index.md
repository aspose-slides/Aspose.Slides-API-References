---
title: RemoveAt
second_title: Aspose.Slides for .NET API 参考
description: 删除集合指定索引处的项目
type: docs
weight: 110
url: /zh/net/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph.RemoveAt method

删除集合指定索引处的项目。

```csharp
public void RemoveAt(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要删除的项目的从零开始的索引。 |

### 例子

示例:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
mathParagraph.RemoveAt(0);
```

### 也可以看看

* class [MathParagraph](../../mathparagraph)
* 命名空间 [Aspose.Slides.MathText](../../mathparagraph)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->