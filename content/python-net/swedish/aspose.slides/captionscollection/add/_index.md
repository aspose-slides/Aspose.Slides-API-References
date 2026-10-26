---
title: add method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Lägger till WebVTT stängda bildtexter i slutet av samlingen.

### Returnerar

Den tillagda [`ICaptions`](/slides/python-net/sv/aspose.slides/icaptions) instansen.



```python
def add(self, label, file_path):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label | **str** | Etiketten för de stängda bildtexterna. |
| file_path | **str** | Sökvägen till WebVTT-filen. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas om `file_path` är `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om `file_path` är tomt. |


## add(self, label, stream) {#str-iorawiobase}
Lägger till WebVTT stängda bildtexter i slutet av samlingen från en ström.

### Returnerar

Den tillagda [`ICaptions`](/slides/python-net/sv/aspose.slides/icaptions) instansen.



```python
def add(self, label, stream):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label | **str** | Etiketten för de stängda bildtexterna. |
| stream | **io.RawIOBase** | Inmatningsströmmen som innehåller data i WebVTT-format. |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kastas om `stream` är `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas om indata inte är i WebVTT-format. |



### Se även
* klass [`CaptionsCollection`](/slides/python-net/sv/aspose.slides/captionscollection)
* klass [`ICaptions`](/slides/python-net/sv/aspose.slides/icaptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)