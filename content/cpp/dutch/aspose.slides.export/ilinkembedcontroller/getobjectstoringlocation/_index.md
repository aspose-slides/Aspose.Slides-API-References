---
title: GetObjectStoringLocation()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt waar het object moet worden opgeslagen. Deze methode wordt één keer per object-id aangeroepen. Er is niet gegarandeerd dat er niet twee objecten met dezelfde data, semanticName en contentType maar met verschillende id bestaan.
type: docs
weight: 1
url: /nl/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) methode

Bepaalt waar het object moet worden opgeslagen. Deze methode wordt één keer per object-id aangeroepen. Er is geen garantie dat er niet twee objecten met dezelfde data, semanticName en contentType maar met verschillende id bestaan.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| id | **int32_t** | Object-id. Deze id is uniek voor de gehele bewaaroperatie. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Binaire data van het object. Deze parameter kan null zijn, als de binaire data van het object nog niet gegenereerd is. |
| semanticName | [System::String](../../../system/string/) | Korte tekst die de betekenis van het object beschrijft. De controller kan dit gebruiken als onderdeel van de externe objectnaam, maar het is aan de dispatcher om ervoor te zorgen dat namen uniek zijn en alleen toegestane tekens bevatten. |
| contentType | [System::String](../../../system/string/) | MIME-type van het object. |
| recomendedExtension | [System::String](../../../system/string/) | Bestandsnaamextensie, aanbevolen voor dit MIME-type. |

### Retourwaarde

Decision

## Zie ook

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [ILinkEmbedController](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)