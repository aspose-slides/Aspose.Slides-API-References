---
title: Group
second_title: Aspose.Slides für .NET API-Referenz
description: Platziert dieses Element in einer Gruppe mithilfe einer unteren geschweiften Klammer
type: docs
weight: 60
url: /de/aspose.slides.mathtext/mathelementbase/group/
---

## Group() {#group}

Platziert dieses Element in einer Gruppe mithilfe einer unteren geschweiften Klammer

```csharp
public IMathGroupingCharacter Group()
```

### Rückgabewert

Neue Instanz des Typs [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Beispiele

Beispiel:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group();
```

### Siehe auch

* Schnittstelle [IMathGroupingCharacter](../../imathgroupingcharacter)
* Klasse [MathElementBase](../../mathelementbase)
* Namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Assembly [Aspose.Slides](../../../)

---

## Group(char, MathTopBotPositions, MathTopBotPositions) {#group_1}

Platziert dieses Element in einer Gruppe mithilfe eines Gruppierungszeichens wie einer unteren geschweiften Klammer oder einem anderen

```csharp
public IMathGroupingCharacter Group(char character, MathTopBotPositions position, 
    MathTopBotPositions verticalJustification)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| character | Char | Gruppierungszeichen wie UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein anderes |
| position | MathTopBotPositions | Position des Gruppierungszeichens |
| verticalJustification | MathTopBotPositions | Vertikale Ausrichtung des Gruppenzeichens. Gibt die Ausrichtung des Objekts in Bezug auf die Grundlinie an. Zum Beispiel, wenn das Gruppenzeichen über dem Objekt ist, bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, befindet sich die Unterseite des Objekts auf der Grundlinie |

### Rückgabewert

Neue Instanz des Typs [`IMathGroupingCharacter`](../../imathgroupingcharacter)

### Beispiele

Beispiel:

```csharp
[C#]
IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").Group('\u23E1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
```

### Siehe auch

* Schnittstelle [IMathGroupingCharacter](../../imathgroupingcharacter)
* Enum [MathTopBotPositions](../../mathtopbotpositions)
* Klasse [MathElementBase](../../mathelementbase)
* Namensraum [Aspose.Slides.MathText](../../mathelementbase)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->