---
title: add method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
WebVTT zárt feliratokat ad a gyűjtemény végéhez.

### Visszatérési érték

A hozzáadott [`ICaptions`](/slides/python-net/hu/aspose.slides/icaptions) példány.



```python
def add(self, label, file_path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| label | **str** | A zárt feliratok címkéje. |
| file_path | **str** | A WebVTT fájl elérési útja. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kivétel, ha a `file_path` `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a `file_path` üres. |


## add(self, label, stream) {#str-iorawiobase}
WebVTT zárt feliratokat ad a gyűjtemény végéhez egy adatfolyamból.

### Visszatérési érték

A hozzáadott [`ICaptions`](/slides/python-net/hu/aspose.slides/icaptions) példány.



```python
def add(self, label, stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| label | **str** | A zárt feliratok címkéje. |
| stream | **io.RawIOBase** | A bemeneti adatfolyam, amely WebVTT formátumú adatot tartalmaz. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Kivétel, ha a `stream` `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a bemeneti adat nem WebVTT formátumú. |



### Lásd még
* osztály [`CaptionsCollection`](/slides/python-net/hu/aspose.slides/captionscollection)
* osztály [`ICaptions`](/slides/python-net/hu/aspose.slides/icaptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)