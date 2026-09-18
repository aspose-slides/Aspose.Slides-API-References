---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

### Returns

Nowo utworzony [`ISummaryZoomFrame`](/slides/python-net/pl/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks zerowy, w którym należy wstawić ramkę Summary Zoom. |
| x | **float** | Współrzędna x nowej ramki Summary Zoom, w punktach. |
| y | **float** | Współrzędna y nowej ramki Summary Zoom, w punktach. |
| width | **float** | Szerokość nowej ramki Summary Zoom, w punktach. |
| height | **float** | Wysokość nowej ramki Summary Zoom, w punktach. |

### Remarks

Ta metoda tworzy ramkę Summary Zoom, która agreguje łącza podsumowujące dla wszystkich sekcji w prezentacji.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, jeśli prezentacja nie zawiera sekcji lub jeśli docelowy slajd nie należy do żadnej sekcji. |



### See Also
* klasa [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection)
* klasa [`ISummaryZoomFrame`](/slides/python-net/pl/aspose.slides/isummaryzoomframe)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)