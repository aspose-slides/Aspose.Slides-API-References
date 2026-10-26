---
title: set_size method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Setzt die Foliengröße nach Typ und skaliert den bestehenden Inhalt.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/de/aspose.slides/slidesizetype) | Die vordefinierte Foliengröße, die angewendet werden soll. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/de/aspose.slides/slidesizescaletype) | Der zu verwendende Skalierungsmodus für den Inhalt. |

### Bemerkungen
Durch die Zuweisung eines anderen Wertes als [`SlideSizeType.CUSTOM`](/slides/python-net/de/aspose.slides/slidesizetype/CUSTOM) wird die [`SlideSize.size`](/slides/python-net/de/aspose.slides/slidesize/size) basierend auf dem ausgewählten Typ angepasst, während [`SlideSize.orientation`](/slides/python-net/de/aspose.slides/slidesize/orientation) erhalten bleibt.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Setzt die Folienabmessungen explizit und skaliert den bestehenden Inhalt.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | **float** | Die neue Folienbreite in Punkten. |
| height | **float** | Die neue Folienhöhe in Punkten. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/de/aspose.slides/slidesizescaletype) | Der zu verwendende Skalierungsmodus für den Inhalt. |

### Bemerkungen
Dies setzt die [`SlideSize.type`](/slides/python-net/de/aspose.slides/slidesize/type)-Eigenschaft auf [`SlideSizeType.CUSTOM`](/slides/python-net/de/aspose.slides/slidesizetype/CUSTOM) zurück und legt das [`SlideSize.orientation`](/slides/python-net/de/aspose.slides/slidesize/orientation) fest.

### Siehe auch
* Klasse [`SlideSize`](/slides/python-net/de/aspose.slides/slidesize)
* Aufzählung [`SlideSizeScaleType`](/slides/python-net/de/aspose.slides/slidesizescaletype)
* Aufzählung [`SlideSizeType`](/slides/python-net/de/aspose.slides/slidesizetype)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)