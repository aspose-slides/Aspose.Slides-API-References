---
title: Subscript
second_title: Aspose.Slides for .NET API 参考
description: 下标参数
type: docs
weight: 30
url: /zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/
---
## MathRightSubSuperscriptElement.Subscript property

下标参数

```csharp
public IMathElement Subscript { get; }
```

### 例子

示例:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sub = subsuperscript.Subscript;
```

### 也可以看看

* interface [IMathElement](../../imathelement)
* class [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* 命名空间 [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* 部件 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
