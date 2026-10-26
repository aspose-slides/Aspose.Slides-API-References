---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/ichartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
If collection already contains data point with index `index` then returns this data point.
            If collection doesn't contains data point with index `index`==N
            (when number of data points in this collection is less or equal then N)
            then adds deficient data points and returns last (which has requested index).
            For example, collection indexes are {0, 1, 2}, and requested index is 5.
            Then method adds deficient data points: {0, 1, 2, 3, 4, 5}. And returns data point with index 5.

### Возвращаемое значение

Возвращает точку данных с запрошенным индексом.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс. |



### См. также
* класс [`IChartDataPoint`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint)
* класс [`IChartDataPointCollection`](/slides/python-net/ru/aspose.slides.charts/ichartdatapointcollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)