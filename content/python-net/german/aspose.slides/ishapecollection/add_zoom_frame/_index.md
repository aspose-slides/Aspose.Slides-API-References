---
title: add_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Form-Sammlung hinzu.

### Rückgabewert

Der neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Das [`ISlide`](/slides/python-net/de/aspose.slides/islide) , auf das der Zoom-Frame verweist;<br/><br/>            muss zu dieser Präsentation gehören. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Folie nicht zur aktuellen Präsentation gehört. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Form-Sammlung hinzu.

### Rückgabewert

Der neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Das [`ISlide`](/slides/python-net/de/aspose.slides/islide) , auf das der Zoom-Frame verweist;<br/><br/>            muss zu dieser Präsentation gehören. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das Bild für die referenzierte Folie [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Folie nicht zur aktuellen Präsentation gehört. |



### Siehe auch
* Klasse [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Klasse [`ISlide`](/slides/python-net/de/aspose.slides/islide)
* Klasse [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)