---
title: GetUrl()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt eine URL zu einem externen Objekt zurück. Diese Methode wird immer aufgerufen, wenn ILinkEmbedController::GetObjectStoringLocation LinkEmbedDecision::Link zurückgegeben hat, und kann aufgerufen werden, wenn ILinkEmbedController::GetObjectStoringLocation LinkEmbedDecision::Embed zurückgegeben hat, aber das Einbetten ist unmöglich. Kann mehrfach für dieselbe Objekt-ID aufgerufen werden."
type: docs
weight: 14
url: /de/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) Methode

Gibt eine URL zu einem externen Objekt zurück. Diese Methode wird immer aufgerufen, wenn [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Link](../../linkembeddecision/) zurückgegeben hat, und kann aufgerufen werden, wenn [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) [LinkEmbedDecision::Embed](../../linkembeddecision/) zurückgegeben hat, aber das Einbetten ist unmöglich. Kann mehrfach für dieselbe Objekt-ID aufgerufen werden.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | **int32_t** | Objekt-ID. Diese ID ist operationweit eindeutig. |
| referrer | **int32_t** | ID des referenzierenden Objekts oder 0, wenn das Objekt vom Root-Dokument referenziert wird. Kann verwendet werden, um einen relativen Link zu erzeugen. |

### Rückgabewert

URL des externen Objekts oder null, wenn dieses Objekt ignoriert werden soll.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ILinkEmbedController](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)