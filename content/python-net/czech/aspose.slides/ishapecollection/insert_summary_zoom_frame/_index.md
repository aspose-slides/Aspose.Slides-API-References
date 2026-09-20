---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Vytvoří nový rámec Summary Zoom a vloží jej do kolekce tvarů na určeném indexu.

### Vrací

Nově vytvořený [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index, na který se má vložit rámec Summary Zoom. |
| x | **float** | Souřadnice x nového rámce Summary Zoom v bodech. |
| y | **float** | Souřadnice y nového rámce Summary Zoom v bodech. |
| width | **float** | Šířka nového rámce Summary Zoom v bodech. |
| height | **float** | Výška nového rámce Summary Zoom v bodech. |

### Poznámky

Tato metoda vytváří rámec Summary Zoom, který shromažďuje odkazy na shrnutí pro všechny sekce v prezentaci.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud prezentace neobsahuje žádné sekce, nebo pokud cílový snímek nepatří do žádné sekce. |



### Viz také
* třída [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection)
* třída [`ISummaryZoomFrame`](/slides/python-net/cs/aspose.slides/isummaryzoomframe)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)