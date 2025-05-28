---
title: Subíndice
second_title: Aspose.Slides para .NET Referencia de API
description: Argumento de subíndice
type: docs
weight: 30
url: /es/aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript/
---

## Propiedad MathRightSubSuperscriptElement.Subscript

Argumento de subíndice

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
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sub = subsuperscript.Subscript;
```

### Véase También

* interfaz [IMathElement](../../imathelement)
* clase [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->