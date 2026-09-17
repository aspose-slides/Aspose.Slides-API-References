---
title: add_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formensammlung hinzu.

### Rückgabewert

Das neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Der x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | **float** | Der y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Der von dem Zoom-Frame referenzierte [`ISlide`](/slides/python-net/de/aspose.slides/islide);<br/><br/>            muss zu dieser Präsentation gehören. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ausgelöst, wenn die referenzierte Folie nicht zur aktuellen Präsentation gehört. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formensammlung hinzu.

### Rückgabewert

Das neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Der x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | **float** | Der y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Der von dem Zoom-Frame referenzierte [`ISlide`](/slides/python-net/de/aspose.slides/islide);<br/><br/>            muss zu dieser Präsentation gehören. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das Bild für die referenzierte Folie [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ausgelöst, wenn die referenzierte Folie nicht zur aktuellen Präsentation gehört. |



### Siehe auch
* Klasse [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* Klasse [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* Klasse [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)