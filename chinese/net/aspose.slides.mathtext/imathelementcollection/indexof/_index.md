---
title: IndexOf
second_title: Aspose.Slides for .NET API 参考
description: 确定集合中特定数学元素的索引
type: docs
weight: 80
url: /zh/net/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection.IndexOf method

确定集合中特定数学元素的索引。

```csharp
public int IndexOf(IMathElement item)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| item | IMathElement | 要在集合中定位的元素。 |

### 返回值

*item*的索引（如果在集合中找到）；否则，-1。

### 例子

示例:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
int index = collection.IndexOf(plusElement);
```

### 也可以看看

* interface [IMathElement](../../imathelement)
* interface [IMathElementCollection](../../imathelementcollection)
* 命名空间 [Aspose.Slides.MathText](../../imathelementcollection)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->