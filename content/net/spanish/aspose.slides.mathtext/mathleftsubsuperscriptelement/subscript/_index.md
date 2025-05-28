---
title: Subíndice
second_title: Referencia de API de Aspose.Slides para .NET
description: Subíndice
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathleftsubsuperscriptelement/subscript/
---

## Propiedad MathLeftSubSuperscriptElement.Subscript

Subíndice

```csharp
public IMathElement Subscript { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sub = leftSubSuperscript.Subscript;
```

### Ver también

* interface [IMathElement](../../imathelement)
* class [MathLeftSubSuperscriptElement](../../mathleftsubsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../mathleftsubsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->