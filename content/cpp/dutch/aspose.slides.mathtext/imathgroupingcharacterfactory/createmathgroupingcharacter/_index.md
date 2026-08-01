---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een wiskundig groeperingskarakter
type: docs
weight: 1
url: /nl/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) methode

Maakt een wiskundig groeperingskarakter

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | wiskundig element om het groeperingskarakter toe te passen |
| character | char16_t | groeperingskarakter |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | positie van het groeperingskarakter |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | verticale uitlijning |

### Retourwaarde

nieuw groeperingskarakterelement

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) methode

Maakt een wiskundig groeperingskarakter

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | wiskundig element om het groeperingskarakter toe te passen |

### Retourwaarde

nieuw groeperingskarakterelement

## Zie ook

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)