---
title: GetObjectStoringLocation()
second_title: Aspose.Slides för C++ API-referens
description: Avgör var objektet ska lagras. Denna metod anropas en gång för varje objekt-id. Det garanteras inte att det inte finns två objekt med samma data, semanticName och contentType men med olika id.
type: docs
weight: 1
url: /sv/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) metod


Avgör var objektet ska lagras. Denna metod anropas en gång för varje objekt-id. Det garanteras inte att det inte finns två objekt med samma data, semanticName och contentType men med olika id.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | **int32_t** | Objekt-id. Detta id är unikt för hela operationen. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Objektets binära data. Denna parameter kan vara null om objektets binära data ännu inte har genererats. |
| semanticName | [System::String](../../../system/string/) | Kort text som beskriver objektets betydelse. Kontrollen kan använda detta som en del av det externa objektnamnet, men det är upp till dispatchern att säkerställa att namn är unika och endast innehåller tillåtna tecken. |
| contentType | [System::String](../../../system/string/) | Objektets MIME-typ. |
| recomendedExtension | [System::String](../../../system/string/) | Filnamnstillägg, rekommenderat för denna MIME-typ. |

### Returvärde

Beslut

## Se även

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)