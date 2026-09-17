---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Erstellt einen neuen Summary Zoom frame und fügt ihn an der angegebenen Position in die Shape-Sammlung ein.

### Returns

Der neu erstellte [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der Summary Zoom frame eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen Summary Zoom frame, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Summary Zoom frame, in Punkten. |
| width | **float** | Die Breite des neuen Summary Zoom frame, in Punkten. |
| height | **float** | Die Höhe des neuen Summary Zoom frame, in Punkten. |

### Remarks

Diese Methode erstellt einen Summary Zoom frame, der Summary-Links für alle Abschnitte in der Präsentation aggregiert.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Wird ausgelöst, wenn die Präsentation keine Abschnitte enthält oder die Zielfolie nicht zu einem Abschnitt gehört. |



### See Also
* Klasse [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)