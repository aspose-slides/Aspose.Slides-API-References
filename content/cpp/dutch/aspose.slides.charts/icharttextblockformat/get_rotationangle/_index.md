---
title: get_RotationAngle()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft de aangepaste rotatie aan die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als deze niet is gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is gespecificeerd, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lees float.
type: docs
weight: 235
url: /nl/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() methode


Bepaalt de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben naast de rotatie die op de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lees **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Opmerkingen


Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft. Daarnaast heeft het tekstgedeelte zelf een rotatie van -90 graden tegen de klok in. Vervolgens zou de resulterende vorm gedraaid lijken, maar zou de tekst erin verschijnen alsof deze helemaal niet gedraaid was. 
## Zie ook

* Klasse [IChartTextBlockFormat](../)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)