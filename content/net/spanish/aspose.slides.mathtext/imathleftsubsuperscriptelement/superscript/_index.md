---
title: Superscript
second_title: Referencia de API de Aspose.Slides para .NET
description: Superíndice
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathleftsubsuperscriptelement/superscript/
---

## Propiedad IMathLeftSubSuperscriptElement.Superscript

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
* interfaz [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathleftsubsuperscriptelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->