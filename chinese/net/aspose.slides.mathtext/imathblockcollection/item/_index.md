---
title: Item
second_title: Aspose.Slides for .NET API 参考
description: 获取指定索引处的项目 只读IMathBlockaspose.slides.mathtext/imathblock
type: docs
weight: 30
url: /zh/net/aspose.slides.mathtext/imathblockcollection/item/
---
## IMathBlockCollection indexer

获取指定索引处的项目。 只读[`IMathBlock`](../../imathblock)。

```csharp
public IMathBlock this[int index] { get; set; }
```

| 范围 | 描述 |
| --- | --- |
| index | 要获取的项目的从零开始的索引 |

### 返回值

数学文本块。

### 例子

示例:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
blockCollection.Add(new MathBlock(new MathematicalText("block1")));
blockCollection.Add(new MathBlock(new MathematicalText("block2")));
IMathBlock block = blockCollection[1];
```

### 也可以看看

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* 命名空间 [Aspose.Slides.MathText](../../imathblockcollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->