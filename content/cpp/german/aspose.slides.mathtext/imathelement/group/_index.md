---
title: Group()
second_title: Aspose.Slides für die C++ API-Referenz
description: Platziert dieses Element in einer Gruppe mithilfe einer geschweiften Klammer nach unten
type: docs
weight: 248
url: /de/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() Methode

Platziert dieses Element in einer Gruppe mithilfe einer geschweiften Klammer nach unten

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Rückgabewert

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Bemerkungen



Beispiel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) Methode


Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, z. B. einer geschweiften Klammer nach unten oder einem anderen

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| character | char16_t | Gruppierungszeichen wie BOTTOM CURLY BRACKET (U+23DF) oder ein anderes |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position des Gruppierungszeichens |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertikale Ausrichtung des Gruppierungszeichens. Gibt die Ausrichtung des Objekts relativ zur Grundlinie an. Beispielweise, wenn das Gruppierungszeichen über dem Objekt liegt, bedeutet VerticalJustification von Top, dass die Oberseite des Objekts auf der Grundlinie liegt; wenn VerticalJustification auf Bottom gesetzt ist, liegt die Unterseite des Objekts auf der Grundlinie |

### Rückgabewert

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Bemerkungen



Beispiel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Siehe auch

* Aufzählung [MathTopBotPositions](../../mathtopbotpositions/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klasse [IMathElement](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)