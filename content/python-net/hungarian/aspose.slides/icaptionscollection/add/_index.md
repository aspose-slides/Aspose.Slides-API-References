---
title: add method
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
WebVTT lezárt feliratokat ad a gyűjtemény végéhez.

### Visszatérési érték

A hozzáadott [`ICaptions`](/slides/python-net/hu/aspose.slides/icaptions) példány.



```python
def add(self, label, file_path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| label | **str** | A lezárt feliratok címkéje. |
| file_path | **str** | A WebVTT fájl elérési útja. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `file_path` `None` értékű. |
| **RuntimeError(Proxy error(ArgumentException))** | `file_path` üres. |


## add(self, label, stream) {#str-iorawiobase}
WebVTT lezárt feliratokat ad a gyűjtemény végéhez egy adatfolyamról.

### Visszatérési érték

A hozzáadott [`ICaptions`](/slides/python-net/hu/aspose.slides/icaptions) példány.



```python
def add(self, label, stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| label | **str** | A lezárt feliratok címkéje. |
| stream | **io.RawIOBase** | A WebVTT formátumú adatot tartalmazó bemeneti adatfolyam. |

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `stream` `None` értékű. |
| **RuntimeError(Proxy error(ArgumentException))** | A bemeneti adat nem WebVTT formátumú. |



### Lásd még
* osztály [`ICaptions`](/slides/python-net/hu/aspose.slides/icaptions)
* osztály [`ICaptionsCollection`](/slides/python-net/hu/aspose.slides/icaptionscollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)