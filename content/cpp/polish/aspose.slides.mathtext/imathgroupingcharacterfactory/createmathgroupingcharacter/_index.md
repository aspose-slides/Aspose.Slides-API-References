---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides dla C++ – Referencja API
description: Tworzy znak grupujący w matematyce
type: docs
weight: 1
url: /pl/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metoda

Tworzy znak grupujący w matematyce

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować znak grupujący |
| character | char16_t | znak grupujący |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | pozycja znaku grupującego |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | pionowe wyrównanie |

### Wartość zwracana

nowy element znaku grupującego

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metoda

Tworzy znak grupujący w matematyce

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | element matematyczny, do którego zastosować znak grupujący |

### Wartość zwracana

nowy element znaku grupującego

## Zobacz także

* Wyliczenie [MathTopBotPositions](../../mathtopbotpositions/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathGroupingCharacterFactory](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)