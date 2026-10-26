---
title: Group()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Umístí tento prvek do skupiny pomocí spodní složené závorky
type: docs
weight: 248
url: /cs/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() metoda


Umístí tento prvek do skupiny pomocí spodní složené závorky

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Návratová hodnota

Nová instance typu [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Poznámky



Příklad: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metoda


Umístí tento prvek do skupiny pomocí znaků pro seskupování, například spodní složené závorky nebo jiného

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| character | char16_t | Skupinový znak, například SPODNÍ SLOŽENÁ ZÁVORKA (U+23DF) nebo jakýkoli jiný |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Pozice skupinového znaku |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertikální zarovnání skupinového znaku. Určuje, jak je objekt zarovnán vzhledem k základní linii. Například, když je skupinový znak nad objektem, VertikálníZarovnání Top znamená, že horní část objektu leží na základní linii; když je VertikálníZarovnání nastaveno na Bottom, spodní část objektu leží na základní linii |

### Návratová hodnota

Nová instance typu [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Poznámky



Příklad: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Viz také

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)