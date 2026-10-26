---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            If collection doesn't contains data point with index `index`==N
            (when number of data points in this collection is less or equal then N)
            then adds deficient data points and returns last (which has requested index).
            For example, collection indexes are {0, 1, 2}, and requested index is 5.
            Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.

### Rückgabe

Gibt den Datenpunkt mit dem gewünschten Index zurück.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index. |



### Siehe auch
* Klasse [`IChartDataPoint`](/slides/python-net/de/aspose.slides.charts/ichartdatapoint)
* Klasse [`IChartDataPointCollection`](/slides/python-net/de/aspose.slides.charts/ichartdatapointcollection)
* Modul [`aspose.slides.charts`](/slides/python-net/de/aspose.slides.charts)
* Bibliothek [`Aspose.Slides`](/slides/python-net)