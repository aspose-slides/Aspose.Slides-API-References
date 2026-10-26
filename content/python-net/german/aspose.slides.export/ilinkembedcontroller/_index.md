---
title: ILinkEmbedController class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ilinkembedcontroller/
---
## ILinkEmbedController Klasse

Callback-Schnittstelle verwendet, um zu bestimmen, wie das Objekt beim Speichern verarbeitet werden soll.

Der Typ ILinkEmbedController stellt die folgenden Mitglieder bereit:

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension)`](/slides/python-net/de/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/#int-bytes-str-str-str) | Bestimmt, wo das Objekt gespeichert werden soll.<br/>            Diese Methode wird einmal pro Objekt-ID aufgerufen.<br/>            Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType, aber unterschiedlichen IDs gibt. |
| [`get_url(self, id, referrer)`](/slides/python-net/de/aspose.slides.export/ilinkembedcontroller/get_url/#int-int) | Gibt eine URL zu einem externen Objekt zurück.<br/>            Diese Methode wird immer aufgerufen, wenn **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.LINK`](/slides/python-net/de/aspose.slides.export/linkembeddecision/LINK) zurückgegeben hat und kann aufgerufen werden, wenn **Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste** [`LinkEmbedDecision.EMBED`](/slides/python-net/de/aspose.slides.export/linkembeddecision/EMBED) zurückgegeben hat, aber das Einbetten ist nicht möglich.<br/>            Kann mehrmals für die gleiche Objekt-ID aufgerufen werden. |
| [`save_external(self, id, entity_data)`](/slides/python-net/de/aspose.slides.export/ilinkembedcontroller/save_external/#int-bytes) | Speichert externes Objekt. |


### Siehe auch
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)