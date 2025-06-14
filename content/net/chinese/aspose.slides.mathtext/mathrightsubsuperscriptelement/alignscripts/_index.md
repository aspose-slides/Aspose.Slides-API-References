---
title: AlignScripts
second_title: Aspose.Sildes for .NET API Reference
description: 指定下标/上标的对齐方式。当为真时，下标和上标在水平方向上对齐。当为假时，它们与基形的形状相关联。默认值为假。
type: docs
weight: 20
url: /zh/aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts/
---

## MathRightSubSuperscriptElement.AlignScripts property

指定下标/上标的对齐方式。当为真时，下标和上标在水平方向上对齐。当为假时，它们与基形的形状相关联。默认值为假。

```csharp
public bool AlignScripts { get; set; }
```

### 示例

示例：

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
subsuperscript.AlignScripts = true;
```

### 另请参见

* class [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->