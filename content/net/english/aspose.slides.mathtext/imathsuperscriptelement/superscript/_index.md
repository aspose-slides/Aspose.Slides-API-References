---
title: Superscript
second_title: Aspose.Sildes for .NET API Reference
description: Superscript
type: docs
weight: 30
url: /aspose.slides.mathtext/imathsuperscriptelement/superscript/
---

## IMathSuperscriptElement.Superscript property

Superscript

```csharp
public IMathElement Superscript { get; }
```

### Examples

Example:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement superscript = new MathematicalText("i");
IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
IMathElement super = superscriptElement.Superscript;
```

### See Also

* interface [IMathElement](../../imathelement)
* interface [IMathSuperscriptElement](../../imathsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../imathsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
