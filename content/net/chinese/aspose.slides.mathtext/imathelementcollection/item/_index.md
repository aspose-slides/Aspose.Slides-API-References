---
title: Item
second_title: Aspose.Sildes for .NET API Reference
description: 获取指定索引处的元素。只读 IMathElementaspose.slides.mathtext/imathelement。
type: docs
weight: 30
url: /zh/aspose.slides.mathtext/imathelementcollection/item/
---

## IMathElementCollection 索引器

获取指定索引处的元素。只读 [`IMathElement`](../../imathelement)。

```csharp
public IMathElement this[int index] { get; }
```

| 参数 | 描述 |
| --- | --- |
| index | 要获取的项的零基础索引 |

### 示例

示例：

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
IMathElement firstElem = collection[0];
```

### 另请参见

* 接口 [IMathElement](../../imathelement)
* 接口 [IMathElementCollection](../../imathelementcollection)
* 命名空间 [Aspose.Slides.MathText](../../imathelementcollection)
* 程序集 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
