---
title: IMathLeftSubSuperscriptElement
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica el objeto Sub-Superscript que consiste en una base y un subíndice y superíndice colocados a la izquierda de la base.
type: docs
weight: 8060
url: /es/aspose.slides.mathtext/imathleftsubsuperscriptelement/
---

## Interfaz IMathLeftSubSuperscriptElement

Especifica el objeto Sub-Superscript, que consiste en una base y un subíndice y superíndice colocados a la izquierda de la base.

```csharp
public interface IMathLeftSubSuperscriptElement : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/base) { get; } | Argumento base |
| [Subscript](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/subscript) { get; } | Subíndice |
| [Superscript](../../aspose.slides.mathtext/imathleftsubsuperscriptelement/superscript) { get; } | Superíndice |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathLeftSubSuperscriptElement leftSubsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheLeft("i", "j");
```

### Vea También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->