---
title: Superscript
second_title: Referencia de la API Aspose.Slides para .NET
description: Superíndice
type: docs
weight: 30
url: /es/aspose.slides.mathtext/mathleftsubsuperscriptelement/superscript/
---

## Propiedad MathLeftSubSuperscriptElement.Superscript

Superíndice

```csharp
public IMathElement Superscript { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sup = leftSubSuperscript.Superscript;
```

### Véase También

* interfaz [IMathElement](../../imathelement)
* clase [MathLeftSubSuperscriptElement](../../mathleftsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../mathleftsubsuperscriptelement)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->