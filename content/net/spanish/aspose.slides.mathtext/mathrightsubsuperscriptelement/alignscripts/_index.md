---
title: AlignScripts
second_title: Aspose.Sildes para .NET API Reference
description: Especifica la alineación de subíndices/superíndices. Cuando es verdadero, el subíndice y el superíndice están alineados horizontalmente entre sí. Cuando es falso, se ajustan a la forma de la base. El valor predeterminado es falso.
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts/
---

## MathRightSubSuperscriptElement.AlignScripts property

Especifica la alineación de subíndices/superíndices. Cuando es verdadero, el subíndice y el superíndice están alineados horizontalmente entre sí. Cuando es falso, se ajustan a la forma de la base. El valor predeterminado es falso.

```csharp
public bool AlignScripts { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
subsuperscript.AlignScripts = true;
```

### Véase También

* class [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* namespace [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->