---
title: Arguments
second_title: Aspose.Slides for .NET API 参考
description: 一个或多个用分隔符分隔的数学元素
type: docs
weight: 20
url: /zh/aspose.slides.mathtext/mathdelimiter/arguments/
---
## MathDelimiter.Arguments property

一个或多个用分隔符分隔的数学元素

```csharp
public IMathElementCollection Arguments { get; }
```

### 例子

示例:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Join("y").Enclose();
IMathElementCollection arguments = delimiter.Arguments;
```

### 也可以看看

* interface [IMathElementCollection](../../imathelementcollection)
* class [MathDelimiter](../../mathdelimiter)
* 命名空间 [Aspose.Slides.MathText](../../mathdelimiter)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
