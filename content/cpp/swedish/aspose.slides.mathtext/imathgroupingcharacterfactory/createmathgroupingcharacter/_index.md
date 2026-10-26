---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett matematiskt grupperingstecken
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) method

Skapar en matematisk grupperingstecken

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematiskt element för att tillämpa grupperingstecken |
| character | char16_t | grupperingstecken |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | position för grupperingstecken |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertikal justering |

### Returvärde

nytt grupperingstecken-element

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) method

Skapar en matematisk grupperingstecken

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematiskt element för att tillämpa grupperingstecken |

### Returvärde

nytt grupperingstecken-element

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathGroupingCharacterFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)