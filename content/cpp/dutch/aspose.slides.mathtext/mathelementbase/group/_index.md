---
title: Group()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaats dit element in een groep met behulp van een onderste accolade
type: docs
weight: 235
url: /nl/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() methode


Plaatst dit element in een groep met behulp van een onderste accolade

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Retourwaarde

Nieuwe instantie van type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Opmerkingen



Voorbeeld: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) methode


Plaatst dit element in een groep met behulp van een groepeerteken zoals een onderste accolade of een ander teken

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| character | char16_t | Groepeerteken zoals onderste accolade (U+23DF) of een ander |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Positie van groepeerteken |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Verticale uitlijning van het groepeerteken. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepeerteken boven het object staat, VerticalJustification van Top geeft aan dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn |

### Retourwaarde

Nieuwe instantie van type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Opmerkingen



Voorbeeld: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Zie ook

* Enumeratie [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klasse [MathElementBase](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)