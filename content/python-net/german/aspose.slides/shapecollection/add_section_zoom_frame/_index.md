---
title: add_section_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Erstellt einen neuen Section Zoom frame und fügt ihn am Ende der Shape-Sammlung hinzu.

### Rückgabewert

Der neu erstellte [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Section Zoom frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Section Zoom frames, in Punkten. |
| width | **float** | Die Breite des neuen Section Zoom frames, in Punkten. |
| height | **float** | Die Höhe des neuen Section Zoom frames, in Punkten. |
| section | [`ISection`](/slides/python-net/de/aspose.slides/isection) | Der von dem Section Zoom frame referenzierte [`ISection`](/slides/python-net/de/aspose.slides/isection); muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Section nicht zur aktuellen Präsentation gehört oder keine Folien enthält. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Erstellt einen neuen Section Zoom frame mit einem vordefinierten Bild und fügt ihn am Ende der Shape-Sammlung hinzu.

### Rückgabewert

Der neu erstellte [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Section Zoom frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Section Zoom frames, in Punkten. |
| width | **float** | Die Breite des neuen Section Zoom frames, in Punkten. |
| height | **float** | Die Höhe des neuen Section Zoom frames, in Punkten. |
| section | [`ISection`](/slides/python-net/de/aspose.slides/isection) | Der von dem Section Zoom frame referenzierte [`ISection`](/slides/python-net/de/aspose.slides/isection); muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage), das innerhalb des Section Zoom frames angezeigt wird. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Section nicht zur aktuellen Präsentation gehört oder keine Folien enthält. |



### Siehe auch
* Klasse [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* Klasse [`ISection`](/slides/python-net/de/aspose.slides/isection)
* Klasse [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)