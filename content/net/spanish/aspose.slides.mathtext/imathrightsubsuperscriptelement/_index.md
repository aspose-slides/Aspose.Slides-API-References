---
title: IMathRightSubSuperscriptElement
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica el objeto Sub-Superíndice que consta de una base y un subíndice y un superíndice colocados a la derecha de la base.
type: docs
weight: 7730
url: /es/aspose.slides.mathtext/imathrightsubsuperscriptelement/
---
## IMathRightSubSuperscriptElement interface

Especifica el objeto Sub-Superíndice, que consta de una base y un subíndice y un superíndice colocados a la derecha de la base.

```csharp
public interface IMathRightSubSuperscriptElement : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/imathrightsubsuperscriptelement/alignscripts) { get; set; } | Especifica la alineación de subíndice/superíndice. Cuando es verdadero, el subíndice y el superíndice se alinean horizontalmente entre sí. Cuando es falso, se ajustan a la forma de la base. El valor predeterminado es falso. |
| [AsIMathElement](../../aspose.slides.mathtext/imathrightsubsuperscriptelement/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathrightsubsuperscriptelement/base) { get; } | Argumento base |
| [Subscript](../../aspose.slides.mathtext/imathrightsubsuperscriptelement/subscript) { get; } | Subíndice argumento |
| [Superscript](../../aspose.slides.mathtext/imathrightsubsuperscriptelement/superscript) { get; } | Superíndice argumento |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### Ver también

* interface [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
