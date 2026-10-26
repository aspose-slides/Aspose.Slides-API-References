---
title: add_section_zoom_frame method
second_title: Aspose.Slides für Python über .NET API Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Erstellt einen neuen Section Zoom-Frame und fügt ihn am Ende der Shape-Sammlung hinzu.

### Rückgabe

Das neu erstellte [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die X-Koordinate des neuen Section Zoom-Frames in Punkten. |
| y | **float** | Die Y-Koordinate des neuen Section Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Section Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Section Zoom-Frames in Punkten. |
| section | [`ISection`](/slides/python-net/de/aspose.slides/isection) | Der [`ISection`](/slides/python-net/de/aspose.slides/isection) auf den der Section Zoom-Frame verweist; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Section nicht zur aktuellen Präsentation gehört oder keine Folien enthält. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Erstellt einen neuen Section Zoom-Frame mit einem vordefinierten Bild und fügt ihn am Ende der Shape-Sammlung hinzu.

### Rückgabe

Das neu erstellte [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die X-Koordinate des neuen Section Zoom-Frames in Punkten. |
| y | **float** | Die Y-Koordinate des neuen Section Zoom-Frames in Punkten. |
| width | **float** | Die Breite des neuen Section Zoom-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Section Zoom-Frames in Punkten. |
| section | [`ISection`](/slides/python-net/de/aspose.slides/isection) | Der [`ISection`](/slides/python-net/de/aspose.slides/isection) auf den der Section Zoom-Frame verweist; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) zur Anzeige im Section Zoom-Frame. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Section nicht zur aktuellen Präsentation gehört oder keine Folien enthält. |



### Siehe auch
* class [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/de/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe)
* class [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)