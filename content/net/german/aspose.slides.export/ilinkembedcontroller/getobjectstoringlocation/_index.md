---
title: GetObjectStoringLocation
second_title: Aspose.Slides für .NET API Referenz
description: Bestimmt, wo das Objekt gespeichert werden soll. Diese Methode wird einmal für jede Objekt-ID aufgerufen. Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType, jedoch mit unterschiedlicher ID gibt.
type: docs
weight: 10
url: /de/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---

## ILinkEmbedController.GetObjectStoringLocation Methode

Bestimmt, wo das Objekt gespeichert werden soll. Diese Methode wird einmal für jede Objekt-ID aufgerufen. Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType, jedoch mit unterschiedlicher ID gibt.

```csharp
public LinkEmbedDecision GetObjectStoringLocation(int id, byte[] entityData, string semanticName, 
    string contentType, string recomendedExtension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | Int32 | Objekt-ID. Diese ID ist operationweit eindeutig. |
| entityData | Byte[] | Binäre Daten des Objekts. Dieser Parameter kann null sein, wenn die binären Daten des Objekts noch nicht generiert wurden. |
| semanticName | String | Ein kurzer Text, der die Bedeutung des Objekts beschreibt. Der Controller kann dies als Teil des externen Objektnamens verwenden, aber es liegt am Dispatcher, sicherzustellen, dass die Namen eindeutig sind und nur erlaubte Zeichen enthalten. |
| contentType | String | MIME-Typ des Objekts. |
| recomendedExtension | String | Dateinamenerweiterung, die für diesen MIME-Typ empfohlen wird. |

### Rückgabewert

Entscheidung

### Siehe auch

* enum [LinkEmbedDecision](../../linkembeddecision)
* interface [ILinkEmbedController](../../ilinkembedcontroller)
* namespace [Aspose.Slides.Export](../../ilinkembedcontroller)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->