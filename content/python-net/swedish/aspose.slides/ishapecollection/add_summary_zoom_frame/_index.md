---
title: add_summary_zoom_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Skapar en ny Summary Zoom-ram och lägger till den i slutet av shape-samlingen.

### Returnerar

Det nyss skapade [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | x-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya Summary Zoom-ramen, i punkter. |
| width | **float** | Bredden på den nya Summary Zoom-ramen, i punkter. |
| height | **float** | Höjden på den nya Summary Zoom-ramen, i punkter. |

### Anmärkningar

Denna metod skapar en Summary Zoom-ram som samlar ihop sammanfattningslänkar för alla sektioner i presentationen.

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception) | Kastas om det inte finns några sektioner i presentationen, eller om målsliden inte tillhör någon sektion. |



### Se även
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* klass [`ISummaryZoomFrame`](/slides/python-net/sv/aspose.slides/isummaryzoomframe)
* klass [`PptxEditException`](/slides/python-net/sv/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)