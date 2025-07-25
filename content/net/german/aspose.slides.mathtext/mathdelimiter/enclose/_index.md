---
title: Enclose
second_title: Aspose.Slides für .NET API Referenz
description: Umschließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen
type: docs
weight: 90
url: /de/aspose.slides.mathtext/mathdelimiter/enclose/
---

## MathDelimiter.Enclose-Methode

Umschließt ein mathematisches Element in angegebenen Zeichen wie Klammern oder anderen Zeichen als Rahmen

```csharp
public override IMathDelimiter Enclose(char beginningCharacter, char endingCharacter)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| beginningCharacter | Char | Anfangszeichen (normalerweise linke Klammer) |
| endingCharacter | Char | Endzeichen (normalerweise rechte Klammer) |

### Rückgabewert

Wenn *beginningCharacter* und *endingCharacter* null sind, werden die entsprechenden Eigenschaften nur Werte zugewiesen und kein neues Objekt wird erstellt (gibt diese Instanz zurück). Andernfalls wird ein neues mathematisches Element vom Typ Delimiter zurückgegeben, das die angegebenen Zeichen als Rahmen enthält und diese Instanz von [`MathDelimiter`](../../mathdelimiter) darin umschließt.

### Beispiele

Beispiel:

```csharp
[C#]
IMathDelimiter innerDelimiter = new MathematicalText("x").Join(",y").Enclose('{', '}');
IMathDelimiter outerDelimiter = innerDelimiter.Enclose('[', ']');
```

### Siehe auch

* Schnittstelle [IMathDelimiter](../../imathdelimiter)
* Klasse [MathDelimiter](../../mathdelimiter)
* Namespace [Aspose.Slides.MathText](../../mathdelimiter)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->