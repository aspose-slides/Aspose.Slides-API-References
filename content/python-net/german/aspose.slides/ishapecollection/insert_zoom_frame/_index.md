---
title: insert_zoom_frame method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Erstellt einen neuen Zoom-Rahmen und fügt ihn an der angegebenen Position in die Formensammlung ein.

### Rückgabe

Das neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Zoom-Rahmen eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | **float** | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Der [`ISlide`](/slides/python-net/de/aspose.slides/islide), auf den der Zoom-Rahmen verweist. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die referenzierte Folie nicht zur aktuellen Präsentation gehört. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Erstellt einen neuen Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Formensammlung ein.

### Rückgabe

Das neu erstellte [`IZoomFrame`](/slides/python-net/de/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Zoom-Rahmen eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | **float** | Die y-Koordinate des neuen Zoom-rahmens in Punkten. |
| width | **float** | Die Breite des neuen Zoom-rahmens in Punkten. |
| height | **float** | Die Höhe des neuen Zoom-rahmens in Punkten. |
| slide | [`ISlide`](/slides/python-net/de/aspose.slides/islide) | Der [`ISlide`](/slides/python-net/de/aspose.slides/islide), auf den der Zoom-rahmen verweist. |
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