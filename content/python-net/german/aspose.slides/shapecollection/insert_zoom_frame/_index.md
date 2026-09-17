---
title: insert_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Erstellt einen neuen Zoom-Frame und fügt ihn an der angegebenen Position in die Shape-Sammlung ein.

### Rückgabewert

Der neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Das [`ISlide`](/slides/python-net/de/aspose.slides/islide), auf das der Zoom-Frame verweist. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Folie nicht zur aktuellen Präsentation gehört. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Erstellt einen neuen Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Shape-Sammlung ein.

### Rückgabewert

Der neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Das [`ISlide`](/slides/python-net/de/aspose.slides/islide), auf das der Zoom-Frame verweist. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das Bild für die referenzierte Folie [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Folie nicht zur aktuellen Präsentation gehört. |



### Siehe auch
* class [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* class [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe)
* class [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)