---
title: MathParagraph
second_title: Aspose.Slides for .NET API 参考
description: 作为数学块容器的数学段落IMathBlock
type: docs
weight: 8180
url: /zh/net/aspose.slides.mathtext/mathparagraph/
---
## MathParagraph class

作为数学块容器的数学段落（IMathBlock）

```csharp
public class MathParagraph : IMathParagraph
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MathParagraph](mathparagraph#constructor)() | 初始化 MathParagraph 类的新实例。 |
| [MathParagraph](mathparagraph#constructor_1)(IMathBlock) | 初始化 MathParagraph 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Count](../../aspose.slides.mathtext/mathparagraph/count) { get; } | 获取集合中实际包含的元素数。 只读Int32. |
| [Item](../../aspose.slides.mathtext/mathparagraph/item) { get; set; } | 获取指定索引处的项目。 只读[`IMathBlock`](../imathblock). |
| [Justification](../../aspose.slides.mathtext/mathparagraph/justification) { get; set; } | 段落对齐 默认值：CenteredAsGroup |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Add](../../aspose.slides.mathtext/mathparagraph/add)(IMathBlock) | 将 IMathBlock 添加到集合的末尾。 |
| [Clear](../../aspose.slides.mathtext/mathparagraph/clear)() | 从集合中删除所有元素。 |
| [Contains](../../aspose.slides.mathtext/mathparagraph/contains)(IMathBlock) | 确定集合是否包含特定值。 |
| [IndexOf](../../aspose.slides.mathtext/mathparagraph/indexof)(IMathBlock) | 确定集合中特定 IMathBlock 的索引。 |
| [Insert](../../aspose.slides.mathtext/mathparagraph/insert)(int, IMathBlock) | 将 IMathBlock 插入到集合中指定索引处。 |
| [Remove](../../aspose.slides.mathtext/mathparagraph/remove)(IMathBlock) | 从集合中删除第一次出现的特定对象/&gt;. |
| [RemoveAt](../../aspose.slides.mathtext/mathparagraph/removeat)(int) | 删除集合指定索引处的项目。 |
| [WriteAsMathMl](../../aspose.slides.mathtext/mathparagraph/writeasmathml)(Stream) | 保存此内容[`MathParagraph`](../mathparagraph)作为 MathML |

### 例子

示例：

```csharp
[C#]
IAutoShape shape = slide.Shapes.AddMathShape(x, y, width, height);
IMathParagraph mathParagraph = (shape.TextFrame.Paragraphs[0].Portions[0] as MathPortion).MathParagraph;
mathParagraph.Justification = MathJustification.LeftJustified;
```

### 也可以看看

* interface [IMathParagraph](../imathparagraph)
* 命名空间 [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* 部件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
