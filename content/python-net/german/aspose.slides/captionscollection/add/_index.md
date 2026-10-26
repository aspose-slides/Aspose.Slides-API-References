---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Fügt dem Ende der Sammlung geschlossene WebVTT-Untertitel hinzu.

### Rückgabewert

The added [`ICaptions`](/slides/python-net/de/aspose.slides/icaptions) instance.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| label | **str** | Die Bezeichnung der geschlossenen Untertitel. |
| file_path | **str** | Der Pfad zur WebVTT-Datei. |

### Ausnahmen

| Exception | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wird ausgelöst, wenn `file_path` None ist. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn `file_path` leer ist. |


## add(self, label, stream) {#str-iorawiobase}
Fügt dem Ende der Sammlung geschlossene WebVTT-Untertitel aus einem Stream hinzu.

### Rückgabewert

The added [`ICaptions`](/slides/python-net/de/aspose.slides/icaptions) instance.



```python
def add(self, label, stream):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| label | **str** | Die Bezeichnung der geschlossenen Untertitel. |
| stream | **io.RawIOBase** | Der Eingabestream, der Daten im WebVTT-Format enthält. |

### Ausnahmen

| Exception | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wird ausgelöst, wenn `stream` None ist. |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Eingabedaten nicht im WebVTT-Format vorliegen. |



### Siehe auch
* Klasse [`CaptionsCollection`](/slides/python-net/de/aspose.slides/captionscollection)
* Klasse [`ICaptions`](/slides/python-net/de/aspose.slides/icaptions)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)