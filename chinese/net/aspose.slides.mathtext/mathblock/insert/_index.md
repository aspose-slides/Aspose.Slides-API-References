---
title: Insert
second_title: Aspose.Slides for .NET API 参考
description: 将 MathElement 插入到集合中指定索引处
type: docs
weight: 130
url: /zh/net/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock.Insert method

将 MathElement 插入到集合中指定索引处。

```csharp
public void Insert(int index, IMathElement item)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 应插入 MathElement 的从零开始的索引。 |
| item | IMathElement | 要插入的 MathElement。 |

### 例子

示例:

```csharp
[C#]
MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
mathBlock.Add(plusElement);
mathBlock.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### 也可以看看

* interface [IMathElement](../../imathelement)
* class [MathBlock](../../mathblock)
* 命名空间 [Aspose.Slides.MathText](../../mathblock)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->