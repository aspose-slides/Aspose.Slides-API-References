---
title: Superscript
second_title: Referencia de la API de Aspose.Slides para .NET
description: Argumento de superíndice
type: docs
weight: 50
url: /es/aspose.slides.mathtext/imathrightsubsuperscriptelement/superscript/
---

## Propiedad IMathRightSubSuperscriptElement.Superscript

Argumento de superíndice

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
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
IMathElement sup = subsuperscript.Superscript;
```

### Véase también

* interfaz [IMathElement](../../imathelement)
* interfaz [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathrightsubsuperscriptelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->