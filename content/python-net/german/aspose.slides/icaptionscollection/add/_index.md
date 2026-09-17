---
title: add method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Fügt der Sammlung WebVTT-Untertitel am Ende hinzu.

### Rückgabe

Die hinzugefügte [`ICaptions`](/slides/python-net/de/aspose.slides/icaptions) Instanz.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| label | **str** | Das Label der Untertitel. |
| file_path | **str** | Der Pfad zur WebVTT-Datei. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wird ausgelöst, wenn `file_path` `None` ist. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn `file_path` leer ist. |


## add(self, label, stream) {#str-iorawiobase}
Fügt der Sammlung geschlossene WebVTT-Untertitel aus einem Stream am Ende hinzu.

### Rückgabe

Die hinzugefügte [`ICaptions`](/slides/python-net/de/aspose.slides/icaptions) Instanz.



```python
def add(self, label, stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| label | **str** | Das Label der Untertitel. |
| stream | **io.RawIOBase** | Der Eingabestream, der Daten im WebVTT-Format enthält. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wird ausgelöst, wenn `stream` `None` ist. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Eingabedaten nicht im WebVTT-Format vorliegen. |



### Siehe auch
* Klasse [`ICaptions`](/slides/python-net/de/aspose.slides/icaptions)
* Klasse [`ICaptionsCollection`](/slides/python-net/de/aspose.slides/icaptionscollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)