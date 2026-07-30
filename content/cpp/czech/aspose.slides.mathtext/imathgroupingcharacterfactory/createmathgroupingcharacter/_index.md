---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytváří matematický seskupovací znak
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) metoda


Vytváří matematický seskupovací znak

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje seskupovací znak |
| character | char16_t | seskupovací znak |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | pozice seskupovacího znaku |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | vertikální zarovnání |

### Návratová hodnota

nový prvek seskupovacího znaku

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) metoda


Vytváří matematický seskupovací znak

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematický prvek, na který se aplikuje seskupovací znak |

### Návratová hodnota

nový prvek seskupovacího znaku

## Viz také

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathGroupingCharacterFactory](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)