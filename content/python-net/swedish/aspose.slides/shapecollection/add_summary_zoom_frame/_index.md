---
title: add_summary_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Skapar en ny Summary Zoom-ram och lägger till den i slutet av shape-samlingen.

### Returnerar

Den nyss skapade [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Summary Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Summary Zoom-ramen, i punkter. |

### Anmärkningar

Denna metod skapar en ny Summary Zoom och placerar en samling objekt i den för alla avsnitt i denna presentation.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om det inte finns några avsnitt i presentationen, eller om target slide inte tillhör något avsnitt. |



### Se även
* klass [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)