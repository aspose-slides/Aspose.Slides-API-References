---
title: set_VerticalJustification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Verticale uitlijning van groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, betekent VerticalJustification van Top dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn Standaard: Bottom voor Position=Top, en Top voor Position=Bottom"
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) methode

Verticale uitlijning van groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, betekent VerticalJustification van Top dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## Zie ook

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Klasse [IMathGroupingCharacter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)