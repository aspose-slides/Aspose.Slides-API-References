---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří matematický seskupovací znak
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/mathgroupingcharacterfactory/createmathgroupingcharacter/
---
## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metoda

Vytvoří matematický seskupovací znak

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se použije seskupovací znak |
| character | char16_t | seskupovací znak |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | umístění seskupovacího znaku |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertikální zarovnání |

### Návratová hodnota

nový prvek seskupovacího znaku

## MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metoda

Vytvoří matematický seskupovací znak

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se použije seskupovací znak |

### Návratová hodnota

nový prvek seskupovacího znaku

## Viz také

* Výčet [MathTopBotPositions](../../mathtopbotpositions/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathGroupingCharacterFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)