---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides C++ API Hivatkozás
description: Létrehoz egy matematikai csoportosító karaktert
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) method

Létrehoz egy matematikai csoportosító karaktert

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem, amelyre a csoportosító karaktert alkalmazzuk |
| character | char16_t | csoportosító karakter |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | csoportosító karakter pozíciója |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertikális igazítás |

### Visszatérési érték

új csoportosító karakter elem

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) method

Létrehoz egy matematikai csoportosító karaktert

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematikai elem, amelyre a csoportosító karaktert alkalmazzuk |

### Visszatérési érték

új csoportosító karakter elem

## Lásd még

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathGroupingCharacterFactory](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)