---
title: Superscript
second_title: Referencia de la API de Aspose.Slides para .NET
description: Superíndice
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathsuperscriptelement/superscript/
---

## Propiedad MathSuperscriptElement.Superscript

Superíndice

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

### Véase También

* interfaz [IMathElement](../../imathelement)
* clase [MathSuperscriptElement](../../mathsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../mathsuperscriptelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->