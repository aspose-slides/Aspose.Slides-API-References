---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Erstellt einen neuen Summary Zoom frame und fügt ihn in die shape collection an der angegebenen Indexposition ein.

### Rückgabewert

Der neu erstellte [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | The zero-based index at which to insert the Summary Zoom frame. |
| x | **float** | The x-coordinate of the new Summary Zoom frame, in points. |
| y | **float** | The y-coordinate of the new Summary Zoom frame, in points. |
| width | **float** | The width of the new Summary Zoom frame, in points. |
| height | **float** | The height of the new Summary Zoom frame, in points. |

### Bemerkungen

Diese Methode erstellt einen Summary Zoom frame, der summary links für alle Abschnitte in der Präsentation aggregiert.

### Ausnahmen

| Exception | Beschreibung |
| :- | :- |
| [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception) | Thrown if the presentation contains no sections, or if the target slide does not belong to any section. |



### Siehe auch
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Klasse [`ISummaryZoomFrame`](/slides/python-net/de/aspose.slides/isummaryzoomframe)
* Klasse [`PptxEditException`](/slides/python-net/de/aspose.slides/pptxeditexception)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)