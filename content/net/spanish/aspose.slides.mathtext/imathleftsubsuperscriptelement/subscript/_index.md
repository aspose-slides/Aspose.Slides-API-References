---
title: Subscript
second_title: Referencia de API de Aspose.Slides para .NET
description: Subscript
type: docs
weight: 30
url: /es/aspose.slides.mathtext/imathleftsubsuperscriptelement/subscript/
---

## IMathLeftSubSuperscriptElement.Subscript property

Subscript

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

### Ver También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathleftsubsuperscriptelement)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->