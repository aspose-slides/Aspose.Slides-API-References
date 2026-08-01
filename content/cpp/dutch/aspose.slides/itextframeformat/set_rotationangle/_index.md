---  
title: set_RotationAngle()  
second_title: Aspose.Slides voor C++ API-referentie  
description: Bepaalt de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben die bovenop de rotatie van de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Schrijf float.  
type: docs  
weight: 352  
url: /nl/aspose.slides/itextframeformat/set_rotationangle/  
---
## ITextFrameFormat::set_RotationAngle(float) methode


Specificeert de aangepaste rotatie die wordt toegepast op de tekst binnen de begrenzende rechthoek. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben die bovenop de rotatie van de tekst zelf wordt toegepast. De resulterende waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Schrijf **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Opmerkingen


Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft die op de vorm wordt toegepast. Daarnaast heeft de tekst zelf een rotatie van -90 graden tegen de klok in die op de tekst wordt toegepast. Vervolgens zou de resulterende vorm gedraaid lijken, maar de tekst erin zou lijken alsof deze helemaal niet gedraaid was. 
## Zie ook

* Klasse [ITextFrameFormat](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)