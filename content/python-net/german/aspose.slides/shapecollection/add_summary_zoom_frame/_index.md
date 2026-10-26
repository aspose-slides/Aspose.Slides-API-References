---
title: add_summary_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Erstellt einen neuen Summary Zoom-Frame und fügt ihn am Ende der Shape-Sammlung hinzu.

### Rückgabewert

Das neu erstellte [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Summary Zoom-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Summary Zoom-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Summary Zoom-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Summary Zoom-Frames, in Punkten. |

### Bemerkungen

Diese Methode erstellt ein neues Summary Zoom und legt eine Sammlung von Objekten für alle Abschnitte dieser Präsentation darin ab.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn es keine Abschnitte in der Präsentation gibt oder die Ziel-Folien nicht zu einem Abschnitt gehört. |



### Siehe auch
* Klasse [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)