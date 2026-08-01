---
title: get_VerticalJustification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Verticale uitlijning van groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter zich boven het object bevindt, VerticalJustification van Top geeft aan dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn Standaard: Bottom voor Position=Top, en Top voor Position=Bottom"
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() methode


Verticale uitlijning van een groepskarakter. Bepaalt de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter zich boven het object bevindt, duidt VerticalJustification van Top aan dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, bevindt de onderkant van het object zich op de basislijn Standaard: Bottom voor Position=Top, en Top voor Position=Bottom

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
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