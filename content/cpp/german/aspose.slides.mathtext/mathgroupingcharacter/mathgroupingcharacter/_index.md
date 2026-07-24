---
title: MathGroupingCharacter()
second_title: Aspose.Slides für C++ API Referenz
description: Initialisiert eine neue Instanz der MathGroupingCharacter class mit dem Standard-Gruppierungszeichen U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /de/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) Konstruktor

Initialisiert eine neue Instanz der [MathGroupingCharacter](../) Klasse mit dem Standard-Gruppierungszeichen U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Basiselement, auf das die Leiste angewendet wird |

## Bemerkungen

Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) Konstruktor

Initialisiert eine neue Instanz der [MathGroupingCharacter](../) Klasse.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Das Basiselement, auf das die Leiste angewendet wird |
| character | char16_t | Gruppierungszeichen |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position des Gruppierungszeichens |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertikale Ausrichtung des Gruppierungszeichens |

## Bemerkungen

Beispiel: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathGroupingCharacter](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)