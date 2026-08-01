---
title: set_VerticalJustification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Verticale uitlijning van het groeperingscharacter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groeperingscharacter zich boven het object bevindt, betekent VerticalJustification van Top dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn Standaard: Bottom voor Position=Top, en Top voor Position=Bottom"
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) methode

Verticale uitlijning van groeperingscharacter. Geeft de uitlijning van het object ten opzichte van de basislijn aan. Bijvoorbeeld, wanneer het groeperingscharacter zich boven het object bevindt, betekent VerticalJustification van Top dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, ligt de onderkant van het object op de basislijn Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## Opmerkingen

Voorbeeld: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Zie ook

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)