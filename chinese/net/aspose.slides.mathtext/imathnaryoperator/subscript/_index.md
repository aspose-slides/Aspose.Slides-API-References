---
title: Subscript
second_title: Aspose.Slides for .NET API 参考
description: 指定下标参数例如在整数的情况下设置下限
type: docs
weight: 40
url: /zh/net/aspose.slides.mathtext/imathnaryoperator/subscript/
---
## IMathNaryOperator.Subscript property

指定下标参数，例如，在整数的情况下，设置下限

```csharp
public IMathElement Subscript { get; }
```

### 例子

示例:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
IMathElement subscriptArg = naryOperator.Subscript;
```

### 也可以看看

* interface [IMathElement](../../imathelement)
* interface [IMathNaryOperator](../../imathnaryoperator)
* 命名空间 [Aspose.Slides.MathText](../../imathnaryoperator)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->