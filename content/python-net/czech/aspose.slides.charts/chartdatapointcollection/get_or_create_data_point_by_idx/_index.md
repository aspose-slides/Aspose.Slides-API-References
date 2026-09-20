---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Pokud kolekce již obsahuje datový bod s indexem `index`, pak vrátí tento datový bod.
Pokud kolekce neobsahuje datový bod s indexem `index`==N (když je počet datových bodů v této kolekci menší nebo roven N), pak přidá chybějící datové body a vrátí poslední (který má požadovaný index).
Například indexy v kolekci jsou {0, 1, 2} a požadovaný index je 5.
Poté metoda přidá chybějící datové body: {0, 1, 2, 3, 4, 5}. A vrátí datový bod s indexem 5.

### Návratová hodnota

Vrací datový bod s požadovaným indexem.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index. |



### Viz také
* třída [`ChartDataPointCollection`](/slides/python-net/cs/aspose.slides.charts/chartdatapointcollection)
* třída [`IChartDataPoint`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)