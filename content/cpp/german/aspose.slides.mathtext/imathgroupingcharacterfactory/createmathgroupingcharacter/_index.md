---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein mathematisches Gruppierungszeichen
type: docs
weight: 1
url: /de/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) Methode


Erstellt ein mathematisches Gruppierungszeichen

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply grouping character |
| character | char16_t | grouping character |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | position of grouping character |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertical justification |

### Rückgabewert

neues Gruppierungszeichen-Element

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) Methode


Erstellt ein mathematisches Gruppierungszeichen

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply grouping character |

### Rückgabewert

neues Gruppierungszeichen-Element

## Siehe auch

* Aufzählung [MathTopBotPositions](../../mathtopbotpositions/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathGroupingCharacterFactory](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)