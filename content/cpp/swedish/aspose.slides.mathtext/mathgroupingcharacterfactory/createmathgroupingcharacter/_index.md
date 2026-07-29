---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett matematiskt grupperingstecken
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metod


Skapar ett matematiskt grupperingstecken

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply grouping character |
| character | char16_t | grouping character |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | position of grouping character |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertical justification |

### Returvärde

nytt grupperingstecken-element

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metod


Skapar ett mathematiskt grupperingstecken

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math element to apply grouping character |

### Returvärde

nytt grupperingstecken-element

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)