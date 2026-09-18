---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Tworzy nową ramkę Summary Zoom i wstawia ją do kolekcji kształtów pod wskazanym indeksem.

### Zwraca

Nowo utworzony [`ISummaryZoomFrame`](/slides/python-net/pl/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy, pod którym wstawia się ramkę Summary Zoom. |
| x | **float** | Współrzędna x nowej ramki Summary Zoom, wyrażona w punktach. |
| y | **float** | Współrzędna y nowej ramki Summary Zoom, wyrażona w punktach. |
| width | **float** | Szerokość nowej ramki Summary Zoom, wyrażona w punktach. |
| height | **float** | Wysokość nowej ramki Summary Zoom, wyrażona w punktach. |

### Uwagi

Ta metoda tworzy ramkę Summary Zoom, która zbiera linki podsumowujące dla wszystkich sekcji w prezentacji.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, jeśli prezentacja nie zawiera sekcji lub jeśli docelowy slajd nie należy do żadnej sekcji. |



### Zobacz także
* klasa [`ISummaryZoomFrame`](/slides/python-net/pl/aspose.slides/isummaryzoomframe)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* klasa [`ShapeCollection`](/slides/python-net/pl/aspose.slides/shapecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)