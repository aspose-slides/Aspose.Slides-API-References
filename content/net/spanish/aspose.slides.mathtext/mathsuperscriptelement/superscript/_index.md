---
title: Superscript
second_title: Aspose.Sildes para .NET Referencia de API
description: Superscript
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathsuperscriptelement/superscript/
---

## MathSuperscriptElement.Superscript propiedad

Superscript

```csharp
public IMathElement Superscript { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement superscript = new MathematicalText("i");
MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
IMathElement super = superscriptElement.Superscript;
```

### Véase también

* interface [IMathElement](../../imathelement)
* class [MathSuperscriptElement](../../mathsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../mathsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->