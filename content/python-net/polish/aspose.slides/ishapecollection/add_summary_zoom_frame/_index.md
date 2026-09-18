---
title: add_summary_zoom_frame method
second_title: Aspose.Slides dla Pythona poprzez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
Tworzy nową ramkę Summary Zoom i dodaje ją na koniec kolekcji kształtów.

### Zwraca

Nowo utworzony [`ISummaryZoomFrame`](/slides/python-net/pl/aspose.slides/isummaryzoomframe).

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| x | **float** | Współrzędna x nowej ramki Summary Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Summary Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Summary Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Summary Zoom, w punktach. |

### Uwagi

Ta metoda tworzy ramkę Summary Zoom, która agreguje linki podsumowujące dla wszystkich sekcji w prezentacji.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Zgłaszany, jeśli w prezentacji nie ma sekcji lub jeśli docelowy slajd nie należy do żadnej sekcji. |

### Zobacz także
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* klasa [`ISummaryZoomFrame`](/slides/python-net/pl/aspose.slides/isummaryzoomframe)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)