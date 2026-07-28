---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy znak grupujący matematyczny
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) method


Tworzy znak grupujący matematyczny

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować znak grupujący |
| character | char16_t | znak grupujący |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | pozycja znaku grupującego |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | wyrównanie pionowe |

### Wartość zwracana

nowy element grupujący

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) method


Tworzy znak grupujący matematyczny

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować znak grupujący |

### Wartość zwracana

nowy element grupujący

## Zobacz także

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacterFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)