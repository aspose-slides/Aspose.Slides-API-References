---
title: Group()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst dit element in een groep met behulp van een onderste accolade
type: docs
weight: 248
url: /nl/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() methode


Plaatst dit element in een groep met behulp van een onderste accolade

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Retourwaarde

Nieuwe instantie van type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Opmerkingen



Voorbeeld: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) methode


Plaatst dit element in een groep met behulp van een groepeerteken, zoals een onderste accolade of een ander

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| character | char16_t | Groeperingsteken zoals BOTTOM CURLY BRACKET (U+23DF) of een ander |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Positie van het groepeerteken |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Verticale uitlijning van het groeps-teken. Specificeert de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groeps-teken zich boven het object bevindt, VerticalJustification van Top geeft aan dat de bovenkant van het object op de basislijn ligt; wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn |

### Retourwaarde

Nieuwe instantie van type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Opmerkingen



Voorbeeld: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Zie ook

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)