---
title: AlignScripts
second_title: Aspose.Slides para .NET Referencia de API
description: Especifica la alineación de subíndices/superíndices. Cuando es verdadero, los subíndices y superíndices están alineados horizontalmente entre sí. Cuando es falso, están ajustados a la forma de la base. El valor predeterminado es falso.
type: docs
weight: 10
url: /es/aspose.slides.mathtext/imathrightsubsuperscriptelement/alignscripts/
---

## IMathRightSubSuperscriptElement.AlignScripts property

Especifica la alineación de subíndices/superíndices. Cuando es verdadero, los subíndices y superíndices están alineados horizontalmente entre sí. Cuando es falso, están ajustados a la forma de la base. El valor predeterminado es falso.

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

### Vea también

* interfaz [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* espacio de nombres [Aspose.Slides.MathText](../../imathrightsubsuperscriptelement)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->