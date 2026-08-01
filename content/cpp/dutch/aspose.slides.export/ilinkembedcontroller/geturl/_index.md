---
title: GetUrl()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert een URL naar een extern object. Deze methode wordt altijd aangeroepen als ILinkEmbedController::GetObjectStoringLocation LinkEmbedDecision::Link retourneerde en kan worden aangeroepen als ILinkEmbedController::GetObjectStoringLocation LinkEmbedDecision::Embed retourneerde, maar insluiting is onmogelijk. Kan meerdere keren worden aangeroepen voor dezelfde object-id."
type: docs
weight: 14
url: /nl/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) methode


Retourneert een URL naar een extern object. Deze methode wordt altijd aangeroepen als [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Link](../../linkembeddecision/) retourneerde en kan worden aangeroepen als [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Embed](../../linkembeddecision/) retourneerde, maar insluiting is onmogelijk. Kan meerdere keren worden aangeroepen voor dezelfde object-id.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | **int32_t** | Object-id. Deze id is gedurende de hele bewerking uniek. |
| referrer | **int32_t** | id van het verwijzende object of 0, als het object wordt verwezen door het root-document. Kan worden gebruikt om een relatieve link te genereren. |

### Retourwaarde

Url van extern object of null als dit object moet worden genegeerd.

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [ILinkEmbedController](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)