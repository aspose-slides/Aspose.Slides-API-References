---
title: IMathFunction
second_title: Aspose.Slides für .NET API-Referenz
description: Bestimmt eine Funktion eines Arguments.
type: docs
weight: 8020
url: /de/aspose.slides.mathtext/imathfunction/
---

## IMathFunction-Schnittstelle

Bestimmt eine Funktion eines Arguments.

```csharp
public interface IMathFunction : IMathElement
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathfunction/asimathelement) { get; } | Ermöglicht den Zugriff auf die Basis-IMathElement-Schnittstelle [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathfunction/base) { get; } | Funktionsargument |
| [Name](../../aspose.slides.mathtext/imathfunction/name) { get; } | Funktionsname Zum Beispiel sind die Funktionsnamen sin und cos |

### Beispiele

Beispiel:

```csharp
[C#]
IMathFunction sinX = new MathematicalText("sin").Function("x");
```

### Siehe auch

* Schnittstelle [IMathElement](../imathelement)
* Namensraum [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->