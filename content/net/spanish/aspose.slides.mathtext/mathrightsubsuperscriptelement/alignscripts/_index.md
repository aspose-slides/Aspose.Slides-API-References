---
title: AlignScripts
second_title: Aspose.Slides para .NET Referencia de API
description: Especifica la alineación de subíndice/superíndice. Cuando es verdadero, el subíndice y el superíndice están alineados horizontalmente entre sí. Cuando es falso, están ajustados a la forma de la base. El valor predeterminado es falso.
type: docs
weight: 20
url: /es/aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts/
---

## Propiedad MathRightSubSuperscriptElement.AlignScripts

Especifica la alineación de subíndice/superíndice. Cuando es verdadero, el subíndice y el superíndice están alineados horizontalmente entre sí. Cuando es falso, están ajustados a la forma de la base. El valor predeterminado es falso.

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

### Ver También

* clase [MathRightSubSuperscriptElement](../../mathrightsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../mathrightsubsuperscriptelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->