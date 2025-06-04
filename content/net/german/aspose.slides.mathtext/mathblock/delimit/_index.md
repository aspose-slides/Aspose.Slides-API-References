---
title: Delimit
second_title: Aspose.Slides für .NET API Referenz
description: Trennt Kind-Elemente mit Trennzeichen ohne die Klammern
type: docs
weight: 90
url: /de/aspose.slides.mathtext/mathblock/delimit/
---

## MathBlock.Delimit-Methode

Trennt Kind-Elemente mit Trennzeichen (ohne die Klammern)

```csharp
public IMathDelimiter Delimit(char separatorCharacter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| separatorCharacter | Char | Trennzeichen |

### Rückgabewert

Das Mathe-Element vom Typ [`IMathDelimiter`](../../imathdelimiter)

### Beispiele

Beispiel:

```csharp
[C#]
MathBlock mathBlock = new MathematicalText("x").Join("y");
IMathDelimiter delimiterElement = mathBlock.Delimit('|');
```

### Siehe Auch

* Schnittstelle [IMathDelimiter](../../imathdelimiter)
* Klasse [MathBlock](../../mathblock)
* Namespace [Aspose.Slides.MathText](../../mathblock)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->