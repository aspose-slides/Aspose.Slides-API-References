---
title: set_RotationAngle()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als het niet is gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Als het wel is gespecificeerd, wordt dit onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Schrijf float.
type: docs
weight: 313
url: /nl/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) methode


Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als het niet is gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Als het wel is gespecificeerd, wordt dit onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Schrijf **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```

## Opmerkingen


Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft gekregen. Daarnaast heeft het tekstlichaam zelf een rotatie van -90 graden tegen de klok in gekregen. Dan zou de resulterende vorm gedraaid lijken, maar de tekst erin zou lijken alsof deze helemaal niet gedraaid is. 
## Zie ook

* Klasse [TextFrameFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)