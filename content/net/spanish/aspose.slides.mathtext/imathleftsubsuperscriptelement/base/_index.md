---
title: Base
second_title: Aspose.Sildes para .NET Referencia de la API
description: Argumento base
type: docs
weight: 20
url: /es/aspose.slides.mathtext/imathleftsubsuperscriptelement/base/
---

## IMathLeftSubSuperscriptElement.Base propiedad

Argumento base

```csharp
public IMathElement Base { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement baseElem = leftSubSuperscript.Base;
```

### Ver También

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathleftsubsuperscriptelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->