---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            If collection doesn't contains data point with index `index`==N
            (when number of data points in this collection is less or equal then N)
            then adds deficient data points and returns last (which has requested index).
            For example, collection indexes are {0, 1, 2}, and requested index is 5.
            Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.

### Visszatérési érték

Visszaadja a kért indexű adatpontot.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Index. |



### Lásd még
* osztály [`IChartDataPoint`](/slides/python-net/hu/aspose.slides.charts/ichartdatapoint)
* osztály [`IChartDataPointCollection`](/slides/python-net/hu/aspose.slides.charts/ichartdatapointcollection)
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)