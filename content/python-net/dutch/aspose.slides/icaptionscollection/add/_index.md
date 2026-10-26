---
title: add method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Voegt WebVTT-ondertiteling toe aan het einde van de collectie.

### Retour

De toegevoegde [`ICaptions`](/slides/python-net/nl/aspose.slides/icaptions) instantie.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| label | **str** | Het label van de ondertiteling. |
| file_path | **str** | Het pad naar het WebVTT-bestand. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wordt gegooid als `file_path` `None` is. |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als `file_path` leeg is. |


## add(self, label, stream) {#str-iorawiobase}
Voegt WebVTT-ondertiteling toe aan het einde van de collectie vanaf een stream.

### Retour

De toegevoegde [`ICaptions`](/slides/python-net/nl/aspose.slides/icaptions) instantie.



```python
def add(self, label, stream):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| label | **str** | Het label van de ondertiteling. |
| stream | **io.RawIOBase** | De invoerstroom met gegevens in WebVTT-indeling. |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Wordt gegooid als `stream` `None` is. |
| **RuntimeError(Proxy error(ArgumentException))** | Wordt gegooid als de invoergegevens niet in WebVTT-indeling zijn. |



### Zie ook
* klasse [`ICaptions`](/slides/python-net/nl/aspose.slides/icaptions)
* klasse [`ICaptionsCollection`](/slides/python-net/nl/aspose.slides/icaptionscollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)