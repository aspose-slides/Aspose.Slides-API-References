---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Voegt WebVTT-ondertiteling toe aan het einde van de verzameling.

### Retour

De toegevoegde [`ICaptions`](/slides/python-net/nl/aspose.slides/icaptions) instantie.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| label | **str** | Het label van de gesloten ondertiteling. |
| file_path | **str** | Het pad naar het WebVTT-bestand. |

### Excepties

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wordt gegooid als `file_path` `None` is. |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als `file_path` leeg is. |


## add(self, label, stream) {#str-iorawiobase}
Voegt WebVTT-ondertiteling toe aan het einde van de verzameling vanuit een stream.

### Retour

De toegevoegde [`ICaptions`](/slides/python-net/nl/aspose.slides/icaptions) instantie.



```python
def add(self, label, stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| label | **str** | Het label van de gesloten ondertiteling. |
| stream | **io.RawIOBase** | De input-stream die gegevens in WebVTT-indeling bevat. |

### Excepties

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wordt gegooid als `stream` `None` is. |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de invoergegevens niet in WebVTT-indeling zijn. |



### Zie ook
* klasse [`CaptionsCollection`](/slides/python-net/nl/aspose.slides/captionscollection)
* klasse [`ICaptions`](/slides/python-net/nl/aspose.slides/icaptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)