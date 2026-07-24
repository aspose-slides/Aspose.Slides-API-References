---
title: GetObjectStoringLocation()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, wo das Objekt gespeichert werden soll. Diese Methode wird einmal für jede Objekt-ID aufgerufen. Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType aber mit unterschiedlicher ID gibt.
type: docs
weight: 1
url: /de/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) Methode

Bestimmt, wo das Objekt gespeichert werden soll. Diese Methode wird einmal für jede Objekt-ID aufgerufen. Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType aber mit unterschiedlicher ID gibt.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | **int32_t** | Objekt-ID. Diese ID ist operationsweit eindeutig. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Binärdaten des Objekts. Dieser Parameter kann null sein, wenn die Binärdaten des Objekts noch nicht erzeugt wurden. |
| semanticName | [System::String](../../../system/string/) | Kurzer Text, der die Bedeutung des Objekts beschreibt. Der Controller kann dies als Teil des externen Objektnamens verwenden, aber es liegt am Dispatcher sicherzustellen, dass die Namen eindeutig sind und nur erlaubte Zeichen enthalten. |
| contentType | [System::String](../../../system/string/) | MIME-Typ des Objekts. |
| recomendedExtension | [System::String](../../../system/string/) | Dateinamenerweiterung, die für diesen MIME-Typ empfohlen wird. |

### Rückgabewert

Entscheidung

## Siehe auch

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [ILinkEmbedController](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)