---
title: Group()
second_title: Aspose.Slides für C++ API-Referenz
description: Platziert dieses Element in einer Gruppe mittels einer unteren geschweiften Klammer
type: docs
weight: 235
url: /de/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() Methode


Plaziert dieses Element in einer Gruppe mithilfe einer geschweiften Klammer unten

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Rückgabewert

Neue Instanz vom Typ [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Bemerkungen



Beispiel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) Methode


Plaziert dieses Element in einer Gruppe mithilfe eines Gruppierungszeichens wie einer geschweiften Klammer unten oder einem anderen

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| character | char16_t | Gruppierungszeichen wie UNTERE GESCHWEIFTE KLAMMER (U+23DF) oder ein anderes |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position des Gruppierungszeichens |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispiel: Wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification Top, dass die Oberkante des Objekts auf der Grundlinie liegt; ist VerticalJustification auf Bottom gesetzt, liegt die Unterkante des Objekts auf der Grundlinie |

### Rückgabewert

Neue Instanz vom Typ [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Bemerkungen



Beispiel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klasse [MathElementBase](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)