---
title: set_size method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Legt die Foliengröße nach Typ fest und skaliert vorhandenen Inhalt.


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/de/aspose.slides/slidesizetype) | Die anzuwendende vordefinierte Foliengröße. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/de/aspose.slides/slidesizescaletype) | Der zu verwendende Inhalts-Skalierungsmodus. |

### Hinweise

Durch Zuweisen eines anderen Wertes als [`SlideSizeType.CUSTOM`](/slides/python-net/de/aspose.slides/slidesizetype/CUSTOM) wird die [`ISlideSize.size`](/slides/python-net/de/aspose.slides/islidesize/size) basierend auf dem ausgewählten Typ angepasst, während [`ISlideSize.orientation`](/slides/python-net/de/aspose.slides/islidesize/orientation) erhalten bleibt.


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Legt die Folienabmessungen explizit fest und skaliert vorhandenen Inhalt.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | **float** | Die neue Folienbreite in Punkten. |
| height | **float** | Die neue Folienhöhe in Punkten. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/de/aspose.slides/slidesizescaletype) | Der zu verwendende Inhalts-Skalierungsmodus. |

### Hinweise

Dies setzt die [`ISlideSize.type`](/slides/python-net/de/aspose.slides/islidesize/type)-Eigenschaft auf [`SlideSizeType.CUSTOM`](/slides/python-net/de/aspose.slides/slidesizetype/CUSTOM) zurück und legt die [`ISlideSize.orientation`](/slides/python-net/de/aspose.slides/islidesize/orientation) fest.



### Siehe auch
* Klasse [`ISlideSize`](/slides/python-net/de/aspose.slides/islidesize)
* Aufzählung [`SlideSizeScaleType`](/slides/python-net/de/aspose.slides/slidesizescaletype)
* Aufzählung [`SlideSizeType`](/slides/python-net/de/aspose.slides/slidesizetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)