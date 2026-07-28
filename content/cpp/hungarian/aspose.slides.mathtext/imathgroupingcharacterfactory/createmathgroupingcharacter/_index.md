---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy matematikai csoportosító karaktert
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) method

Létrehoz egy matematikai csoportosító karaktert

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem, amelyre a csoportosító karaktert alkalmazzuk |
| character | char16_t | csoportosító karakter |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | a csoportosító karakter helye |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | függőleges igazítás |

### Visszatérési érték

új csoportosító karakter elem

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) method

Létrehoz egy matematikai csoportosító karaktert

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem, amelyre a csoportosító karaktert alkalmazzuk |

### Visszatérési érték

új csoportosító karakter elem

## Lásd még

* Enumeráció [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathGroupingCharacterFactory](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)