---
title: GetUrl()
second_title: Aspose.Slides för C++ API-referens
description: "Returnerar en URL till ett externt objekt. Denna metod anropas alltid om ILinkEmbedController::GetObjectStoringLocation returnerade LinkEmbedDecision::Link och kan anropas om ILinkEmbedController::GetObjectStoringLocation returnerade LinkEmbedDecision::Embed men inbäddning är omöjlig. Kan anropas flera gånger för samma objekt-id."
type: docs
weight: 14
url: /sv/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) method


Returnerar en URL till ett externt objekt. Denna metod anropas alltid om [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returnerade [LinkEmbedDecision::Link](../../linkembeddecision/) och kan anropas om [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) returnerade [LinkEmbedDecision::Embed](../../linkembeddecision/) men inbäddning är omöjlig. Kan anropas flera gånger för samma objekt-id.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | **int32_t** | Objekt-id. Detta id är sparat operation-wide unikt. |
| referrer | **int32_t** | id för refererande objekt eller 0, om objektet refereras av rotdokumentet. Kan användas för att generera relativ länk. |

### Returvärde

URL för externt objekt eller null om detta objekt ska ignoreras.

## Se även

* Klass [String](../../../system/string/)
* Klass [ILinkEmbedController](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)