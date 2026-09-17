---
title: get_object_storing_location method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.export/ilinkembedcontroller/get_object_storing_location/
weight: 10
---
## get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension) {#int-bytes-str-str-str}
Bestimmt, wo das Objekt gespeichert werden soll.
            Diese Methode wird einmal pro Objekt-ID aufgerufen.
            Es ist nicht garantiert, dass es nicht zwei Objekte mit denselben Daten, semanticName und contentType, aber unterschiedlicher ID gibt.

### Rückgabe

Entscheidung



```python
def get_object_storing_location(self, id, entity_data, semantic_name, content_type, recomended_extension):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| id | **int** | Objekt-ID. Diese ID ist für den gesamten Speicher-Vorgang eindeutig. |
| entity_data | **bytes** | Binärdaten des Objekts. Dieser Parameter kann None sein, wenn die Binärdaten des Objekts noch nicht erzeugt wurden. |
| semantic_name | **str** | Ein kurzer Text, der die Bedeutung des Objekts beschreibt. Der Controller kann dies als Teil des externen Objektnamens verwenden, aber es liegt beim Dispatcher sicherzustellen, dass die Namen eindeutig sind und nur zulässige Zeichen enthalten. |
| content_type | **str** | MIME-Typ des Objekts. |
| recomended_extension | **str** | Dateinamenerweiterung, empfohlen für diesen MIME-Typ. |



### Siehe auch
* Klasse [`ILinkEmbedController`](/slides/python-net/de/aspose.slides.export/ilinkembedcontroller)
* Aufzählung [`LinkEmbedDecision`](/slides/python-net/de/aspose.slides.export/linkembeddecision)
* Modul [`aspose.slides.export`](/slides/python-net/de/aspose.slides.export)
* Bibliothek [`Aspose.Slides`](/slides/python-net)