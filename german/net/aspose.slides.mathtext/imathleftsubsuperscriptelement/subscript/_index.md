---
title: Subscript
second_title: Aspose.Slides für .NET-API-Referenz
description: tiefgestellt
type: docs
weight: 30
url: /de/net/aspose.slides.mathtext/imathleftsubsuperscriptelement/subscript/
---
## IMathLeftSubSuperscriptElement.Subscript property

tiefgestellt

```csharp
public IMathElement Subscript { get; }
```

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sub = leftSubSuperscript.Subscript;
```

### Siehe auch

* interface [IMathElement](../../imathelement)
* interface [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement)
* namensraum [Aspose.Slides.MathText](../../imathleftsubsuperscriptelement)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->