---
title: Group()
second_title: Aspose.Slides pro C++ API Reference
description: Umístí tento prvek do skupiny pomocí dolní složené závorky
type: docs
weight: 235
url: /cs/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() metoda


Umístí tento prvek do skupiny pomocí dolní složené závorky

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Návratová hodnota

Nová instance typu [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Poznámky



Příklad: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metoda


Umístí tento prvek do skupiny pomocí znaku pro seskupení, jako je dolní složená závorka nebo jiný

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position of grouping character |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertikální zarovnání znaku skupiny. Určuje zarovnání objektu vzhledem k základní lince. Například když je znak skupiny nad objektem, VerticalJustification of Top znamená, že horní část objektu leží na základní lince; když je VerticalJustification nastaveno na Bottom, spodní část objektu je na základní lince |

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
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)