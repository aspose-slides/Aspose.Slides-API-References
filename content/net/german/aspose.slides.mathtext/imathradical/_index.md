---
title: IMathRadical
second_title: Aspose.Slides für .NET API-Referenz
description: Spezifiziert die radikale Funktion, die aus einer Basis und einem optionalen Grad besteht. Beispiel für ein radikales Objekt ist √𝑥.
type: docs
weight: 8170
url: /de/aspose.slides.mathtext/imathradical/
---

## IMathRadical-Schnittstelle

Spezifiziert die radikale Funktion, die aus einer Basis und einem optionalen Grad besteht. Beispiel für ein radikales Objekt ist √𝑥.

```csharp
public interface IMathRadical : IMathElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathradical/asimathelement) { get; } | Ermöglicht den Zugriff auf die Basis IMathElement-Schnittstelle [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathradical/base) { get; } | Basis-Argument |
| [Degree](../../aspose.slides.mathtext/imathradical/degree) { get; } | Grad-Argument |
| [HideDegree](../../aspose.slides.mathtext/imathradical/hidedegree) { get; set; } | Grad verbergen. Wenn true, wird der Grad nicht angezeigt, wie in √𝑥 |

### Beispiele

Beispiel:

```csharp
[C#]
IMathRadical radical = new MathematicalText("x").Radical("3"); // Kubikwurzel
```

### Siehe auch

* Schnittstelle [IMathElement](../imathelement)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->