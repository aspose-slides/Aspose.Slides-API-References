---
title: insert_section_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Erstellt einen neuen Section Zoom-Frame und fügt ihn in die Formsammlung an dem angegebenen Index ein.

### Rückgabe

Der neu erstellte [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Section Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Section Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Section Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Section Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Section Zoom-Frames, in Punkten. |
| section | [`ISection`](/slides/python-net/de/aspose.slides/isection) | Die [`ISection`](/slides/python-net/de/aspose.slides/isection) vom Section Zoom-Frame referenziert; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Section nicht zur aktuellen Präsentation gehört oder keine Folien enthält. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Erstellt einen neuen Section Zoom-Frame mit einem vordefinierten Bild und fügt ihn in die Formsammlung an dem angegebenen Index ein.

### Rückgabe

Der neu erstellte [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Section Zoom-Frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Section Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Section Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Section Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Section Zoom-Frames, in Punkten. |
| section | [`ISection`](/slides/python-net/de/aspose.slides/isection) | Die [`ISection`](/slides/python-net/de/aspose.slides/isection) vom Section Zoom-Frame referenziert; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage) | Das Bild, das im Section Zoom-Frame angezeigt werden soll. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Section nicht zur aktuellen Präsentation gehört oder keine Folien enthält. |



### Siehe auch
* Klasse [`IPPImage`](/slides/python-net/de/aspose.slides/ippimage)
* Klasse [`ISection`](/slides/python-net/de/aspose.slides/isection)
* Klasse [`ISectionZoomFrame`](/slides/python-net/de/aspose.slides/isectionzoomframe)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)