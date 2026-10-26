---
title: add_summary_zoom_frame method
second_title: Aspose.Slides pro Python přes .NET referenční příručku API
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Vytvoří nový rámec Summary Zoom a přidá jej na konec kolekce tvarů.

### Návratová hodnota
Nově vytvořený [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe).

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Souřadnice x nového rámce Summary Zoom v bodech. |
| y | **float** | Souřadnice y nového rámce Summary Zoom v bodech. |
| width | **float** | Šířka nového rámce Summary Zoom v bodech. |
| height | **float** | Výška nového rámce Summary Zoom v bodech. |

### Poznámky
Tato metoda vytváří rámec Summary Zoom, který shromažďuje odkazy na souhrny pro všechny sekce v prezentaci.

### Výjimky

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvoláno, pokud v prezentaci neexistují žádné sekce, nebo pokud cílový snímek nepatří do žádné sekce. |

### Viz také
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* třída [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)