---
title: Superscript
second_title: Referencia de la API de Aspose.Slides para .NET
description: Superíndice
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathsuperscriptelement/superscript/
---
## MathSuperscriptElement.Superscript property

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

### Ver también

* interface [IMathElement](../../imathelement)
* class [MathSuperscriptElement](../../mathsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../mathsuperscriptelement)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
