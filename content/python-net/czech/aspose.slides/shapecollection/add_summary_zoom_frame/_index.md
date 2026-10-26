---
title: add_summary_zoom_frame method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/shapecollection/add_summary_zoom_frame/
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


| Parametr | Typ | Popis |
| :- | :- | :- |
| x | **float** | X-souřadnice nového rámce Summary Zoom, v bodech. |
| y | **float** | Y-souřadnice nového rámce Summary Zoom, v bodech. |
| width | **float** | Šířka nového rámce Summary Zoom, v bodech. |
| height | **float** | Výška nového rámce Summary Zoom, v bodech. |

### Poznámky

Tato metoda vytvoří nový Summary Zoom a vloží do něj kolekci objektů pro všechny sekce v této prezentaci.

### Výjimky

| Exception | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud v prezentaci neexistují žádné sekce, nebo pokud cílový snímek nepatří do žádné sekce. |



### Viz také
* třída [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* třída [`ShapeCollection`](/slides/python-net/cs/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)