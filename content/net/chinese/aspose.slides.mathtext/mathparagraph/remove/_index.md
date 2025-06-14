---
title: Remove
second_title: Aspose.Sildes for .NET API Reference
description: 从集合中移除特定对象的第一个实例。
type: docs
weight: 100
url: /zh/aspose.slides.mathtext/mathparagraph/remove/
---

## MathParagraph.Remove 方法

从集合中移除特定对象的第一个实例。

```csharp
public bool Remove(IMathBlock mathBlock)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | IMathBlock | 要从集合中移除的对象。 |

### 返回值

如果 *mathBlock* 成功从集合中移除，则返回 true；否则返回 false。如果 *mathBlock* 在原始集合中未找到，此方法也将返回 false。

### 示例

示例:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Add(new MathBlock(new MathematicalText("x")));
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
mathParagraph.Remove(block);
```

### 另请参阅

* interface [IMathBlock](../../imathblock)
* class [MathParagraph](../../mathparagraph)
* namespace [Aspose.Slides.MathText](../../mathparagraph)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->