---
title: get_RotationAngle()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen het omvattende kader. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben, naast de rotatie die op de tekst zelf wordt toegepast. De resulterende visuele tekstrotatie, samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen float.
type: docs
weight: 300
url: /nl/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() methode


Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen het omvattende kader. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben, naast de rotatie die op de tekst zelf wordt toegepast. De resulterende visuele tekstrotatie, samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Opmerkingen


Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft. Daarnaast heeft het tekstblok zelf een rotatie van -90 graden tegen de klok in. De resulterende vorm zou dan gedraaid lijken, maar de tekst erin zou lijken alsof deze helemaal niet gedraaid is. 
## Zie ook

* Klasse [TextFrameFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)