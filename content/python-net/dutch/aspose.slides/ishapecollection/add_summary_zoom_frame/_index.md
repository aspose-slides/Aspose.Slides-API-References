---
title: add_summary_zoom_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Maakt een nieuw Summary Zoom frame en voegt het toe aan het einde van de vormverzameling.

### Retourwaarde

Het nieuw aangemaakte [`ISummaryZoomFrame`](/slides/python-net/nl/aspose.slides/isummaryzoomframe).



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe Summary Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe Summary Zoom frame, in punten. |

### Opmerkingen

Deze methode maakt een Summary Zoom frame dat samenvattingskoppelingen voor alle secties in de presentatie groepeert.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als er geen secties in de presentatie zijn, of als de doeldia niet tot een sectie behoort. |



### Zie ook
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* klasse [`ISummaryZoomFrame`](/slides/python-net/nl/aspose.slides/isummaryzoomframe)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)