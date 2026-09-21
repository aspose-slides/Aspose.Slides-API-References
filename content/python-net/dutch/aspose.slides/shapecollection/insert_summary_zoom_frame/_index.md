---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Creëert een nieuw Summary Zoom frame en voegt het in de shape collection in op de opgegeven index.

### Retour

Het nieuw aangemaakte [`ISummaryZoomFrame`](/slides/python-net/nl/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nulgebaseerde index waarop het Summary Zoom frame moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe Summary Zoom frame, in punten. |
| width | **float** | De breedte van het nieuwe Summary Zoom frame, in punten. |
| height | **float** | De hoogte van het nieuwe Summary Zoom frame, in punten. |

### Opmerkingen

Deze methode maakt een Summary Zoom frame aan dat samenvattingskoppelingen voor alle secties in de presentatie aggregeert.

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception) | Wordt gegooid als de presentatie geen secties bevat, of als de doel-dia niet tot een sectie behoort. |



### Zie ook
* klasse [`ISummaryZoomFrame`](/slides/python-net/nl/aspose.slides/isummaryzoomframe)
* klasse [`PptxEditException`](/slides/python-net/nl/aspose.slides/pptxeditexception)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)