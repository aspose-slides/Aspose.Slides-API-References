---
title: Remove
second_title: Aspose.Slides for .NET API 参考
description: 从集合中删除第一次出现的特定对象/gt.
type: docs
weight: 90
url: /zh/net/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection.Remove method

从集合中删除第一次出现的特定对象/&gt;.

```csharp
public bool Remove(IMathBlock item)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | IMathBlock | 要从集合中移除的对象。 |

### 返回值

真如果*item*已成功从集合中删除；否则为假。 这个方法也返回 false if*item*未在原始集合中找到/&gt;.

### 例子

示例：

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
blockCollection.Remove(block);
```

### 也可以看看

* interface [IMathBlock](../../imathblock)
* interface [IMathBlockCollection](../../imathblockcollection)
* 命名空间 [Aspose.Slides.MathText](../../imathblockcollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
