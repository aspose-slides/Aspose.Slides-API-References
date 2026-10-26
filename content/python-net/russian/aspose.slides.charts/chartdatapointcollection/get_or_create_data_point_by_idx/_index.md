---
title: get_or_create_data_point_by_idx method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/chartdatapointcollection/get_or_create_data_point_by_idx/
weight: 190
---
## get_or_create_data_point_by_idx(self, index) {#int}
Если коллекция уже содержит точку данных с индексом `index`, то возвращает эту точку данных.  
Если в коллекции нет точки данных с индексом `index`==N  
(когда количество точек данных в этой коллекции меньше или равно N),  
то добавляются недостающие точки данных и возвращается последняя (которая имеет запрошенный индекс).  
Например, индексы в коллекции: {0, 1, 2}, а запрошенный индекс — 5.  
Тогда метод добавляет недостающие точки данных: {0, 1, 2, 3, 4, 5}. И возвращает точку данных с индексом 5.

### Возвращаемое значение

Возвращает точку данных с запрошенным индексом.



```python
def get_or_create_data_point_by_idx(self, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс. |



### Смотрите также
* класс [`ChartDataPointCollection`](/slides/python-net/ru/aspose.slides.charts/chartdatapointcollection)
* класс [`IChartDataPoint`](/slides/python-net/ru/aspose.slides.charts/ichartdatapoint)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)