---
title: Contains
second_title: Aspose.Slides for .NET API 参考
description: 确定集合是否包含特定值
type: docs
weight: 70
url: /zh/net/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph.Contains method

确定集合是否包含特定值。

```csharp
public bool Contains(IMathBlock mathBlock)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| mathBlock | IMathBlock | 要在集合中定位的对象。 |

### 返回值

如果在集合中找到*mathBlock*则为真；否则为假。

### 例子

示例:

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
IMathBlock block = new MathBlock(new MathematicalText("y"));
mathParagraph.Add(block);
bool contains = mathParagraph.Contains(block);
```

### 也可以看看

* interface [IMathBlock](../../imathblock)
* class [MathParagraph](../../mathparagraph)
* 命名空间 [Aspose.Slides.MathText](../../mathparagraph)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->