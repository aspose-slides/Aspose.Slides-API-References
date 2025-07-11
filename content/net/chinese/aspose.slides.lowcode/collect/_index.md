---
title: Collect
second_title: Aspose.Sildes for .NET API Reference
description: 表示一组旨在从 Presentation../aspose.slides/presentation 收集不同类型的模型对象的方法。
type: docs
weight: 7620
url: /zh/aspose.slides.lowcode/collect/
---

## Collect class

表示一组旨在从 [`Presentation`](../../aspose.slides/presentation) 收集不同类型的模型对象的方法。

```csharp
public static class Collect
```

## Methods

| Name | Description |
| --- | --- |
| static [Shapes](../../aspose.slides.lowcode/collect/shapes)(Presentation) | 收集 [`Presentation`](../../aspose.slides/presentation) 中的所有 [`Shape`](../../aspose.slides/shape) 实例。 |

### Examples

```csharp
using (Presentation pres = new Presentation("pres.pptx"))
{
    foreach (Shape shape in Collect.Shapes(pres))
    {
        // ... 修改形状格式或其他属性
    }
}    
```

### See Also

* namespace [Aspose.Slides.LowCode](../../aspose.slides.lowcode)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->