---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Skapar en ny Summary Zoom-ram och infogar den i shape-samlingen på det angivna indexet.

### Returnerar

Det nyss skapade [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där Summary Zoom-ramen ska infogas. |
| x | **float** | X-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Summary Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Summary Zoom-ramen, i punkter. |

### Anmärkningar

Denna metod skapar en Summary Zoom-ram som samlar sammanfattningslänkar för alla avsnitt i presentationen.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om presentationen inte innehåller några avsnitt, eller om målbilder inte tillhör något avsnitt. |



### Se även
* klass [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)