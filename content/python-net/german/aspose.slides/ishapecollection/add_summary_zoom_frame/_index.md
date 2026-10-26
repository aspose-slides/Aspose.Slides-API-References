---
title: add_summary_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Erstellt einen neuen Summary Zoom frame und fügt ihn am Ende der Formensammlung hinzu.

### Rückgabewert

Der neu erstellte [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | **float** | Die x-Koordinate des neuen Summary Zoom frame, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Summary Zoom frame, in Punkten. |
| width | **float** | Die Breite des neuen Summary Zoom frame, in Punkten. |
| height | **float** | Die Höhe des neuen Summary Zoom frame, in Punkten. |

### Anmerkungen

Diese Methode erstellt einen Summary Zoom frame, der Zusammenfassungs-Links für alle Abschnitte in der Präsentation aggregiert.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn es keine Abschnitte in der Präsentation gibt oder wenn die Ziel-Folien nicht zu einem Abschnitt gehört. |



### Siehe auch
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Klasse [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)