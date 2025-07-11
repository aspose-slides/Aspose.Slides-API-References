---
title: Item
second_title: Aspose.Sildes for .NET API Reference
description: 获取指定索引处的项。只读 IMathBlockaspose.slides.mathtext/imathblock。
type: docs
weight: 30
url: /zh/aspose.slides.mathtext/imathblockcollection/item/
---

## IMathBlockCollection 索引器

获取指定索引处的项。只读 [`IMathBlock`](../../imathblock)。

```csharp
public IMathBlock this[int index] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| index | 要获取的项的零基索引 |

### 返回值

一个数学文本的块。

### 示例

示例：

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
blockCollection.Add(new MathBlock(new MathematicalText("block1")));
blockCollection.Add(new MathBlock(new MathematicalText("block2")));
IMathBlock block = blockCollection[1];
```

### 另请参见

* 接口 [IMathBlock](../../imathblock)
* 接口 [IMathBlockCollection](../../imathblockcollection)
* 命名空间 [Aspose.Slides.MathText](../../imathblockcollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->