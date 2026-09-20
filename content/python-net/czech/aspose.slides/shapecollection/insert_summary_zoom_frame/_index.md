---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides pro Python – referenční příručka .NET API
description: 
type: docs
url: /cs/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Vytvoří nový Summary Zoom rámec a vloží jej do sbírky tvarů na zadaném indexu.

### Returns
Nově vytvořený [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe).

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na který se má vložit Summary Zoom rámec. |
| x | **float** | X-souřadnice nového Summary Zoom rámce, v bodech. |
| y | **float** | Y-souřadnice nového Summary Zoom rámce, v bodech. |
| width | **float** | Šířka nového Summary Zoom rámce, v bodech. |
| height | **float** | Výška nového Summary Zoom rámce, v bodech. |

### Remarks
Tato metoda vytváří Summary Zoom rámec, který shromažďuje souhrnné odkazy pro všechny sekce v prezentaci.

### Exceptions

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud prezentace neobsahuje žádné sekce, nebo pokud cílový snímek nepatří do žádné sekce. |

### See Also
* třída [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)