---
title: get_VerticalJustification()
second_title: Aspose.Slides voor C++ API-referentie
description: "Verticale uitlijning van groepskarakter. Specificeert de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, de onderkant van het object op de basislijn. Default: Bottom for Position=Top, and Top for Position=Bottom"
type: docs
weight: 66
url: /nl/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() methode

Verticale uitlijning van groepskarakter. Specificeert de uitlijning van het object ten opzichte van de basislijn. Bijvoorbeeld, wanneer het groepskarakter boven het object staat, VerticalJustification van Top betekent dat de bovenkant van het object op de basislijn valt; wanneer VerticalJustification is ingesteld op Bottom, de onderkant van het object op de basislijn. Standaard: Bottom for Position=Top, and Top for Position=Bottom

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
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