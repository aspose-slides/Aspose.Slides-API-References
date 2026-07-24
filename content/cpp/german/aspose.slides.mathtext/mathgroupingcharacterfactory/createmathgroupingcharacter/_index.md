---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein mathematisches Gruppierungszeichen
type: docs
weight: 1
url: /de/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) Methode

Erstellt ein mathematisches Gruppierungszeichen

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathe-Element zur Anwendung des Gruppierungszeichens |
| character | char16_t | Gruppierungszeichen |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position des Gruppierungszeichens |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertikale Justierung |

### Rückgabewert

neues Gruppierungszeichen-Element

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) Methode

Erstellt ein mathematisches Gruppierungszeichen

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Mathe-Element zur Anwendung des Gruppierungszeichens |

### Rückgabewert

neues Gruppierungszeichen-Element

## Siehe auch

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)