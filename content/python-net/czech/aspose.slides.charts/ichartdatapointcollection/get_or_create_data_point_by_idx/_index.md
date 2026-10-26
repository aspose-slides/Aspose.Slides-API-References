---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Pokud kolekce již obsahuje datový bod s indexem `index`, metoda vrátí tento datový bod.
            Pokud kolekce neobsahuje datový bod s indexem `index`==N (když je počet datových bodů v této kolekci menší nebo roven N), metoda přidá chybějící datové body a vrátí poslední (který má požadovaný index).
            Například indexy v kolekci jsou {0, 1, 2} a požadovaný index je 5. Pak metoda přidá chybějící datové body: {0, 1, 2, 3, 4, 5} a vrátí datový bod s indexem 5.

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
* třída [`IChartDataPoint`](/slides/python-net/cs/aspose.slides.charts/ichartdatapoint)
* třída [`IChartDataPointCollection`](/slides/python-net/cs/aspose.slides.charts/ichartdatapointcollection)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)