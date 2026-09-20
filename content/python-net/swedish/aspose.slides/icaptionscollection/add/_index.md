---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Lägger till WebVTT-undertexter i slutet av samlingen.

### Returns
Den tillagda [`ICaptions`](/slides/python-net/sv/aspose.slides/icaptions)-instansen.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label | **str** | Etiketten för undertexterna. |
| file_path | **str** | Sökvägen till WebVTT-filen. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas om `file_path` är `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om `file_path` är tomt. |


## add(self, label, stream) {#str-iorawiobase}
Lägger till WebVTT-undertexter i slutet av samlingen från en ström.

### Returns
Den tillagda [`ICaptions`](/slides/python-net/sv/aspose.slides/icaptions)-instansen.



```python
def add(self, label, stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label | **str** | Etiketten för undertexterna. |
| stream | **io.RawIOBase** | Ingångsströmmen som innehåller data i WebVTT-format. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas om `stream` är `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om indata inte är i WebVTT-format. |



### Se även
* klass [`ICaptions`](/slides/python-net/sv/aspose.slides/icaptions)
* klass [`ICaptionsCollection`](/slides/python-net/sv/aspose.slides/icaptionscollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)