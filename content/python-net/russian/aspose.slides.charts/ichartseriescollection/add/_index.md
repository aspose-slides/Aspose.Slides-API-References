---
title: add method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.charts/ichartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Создает новую серию диаграммы и добавляет её в коллекцию.

### Возвращаемое значение

Новая серия диаграммы.



```python
def add(self, type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип серии |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Создает новую серию диаграммы из [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) и добавляет её в коллекцию.

### Возвращаемое значение

Добавленная серия диаграммы или серия, уже находящаяся в коллекции.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell) | Ячейка, содержащая имя серии. |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип, задающий тип серии |

### Замечания

Если серия диаграммы, созданная из той же ячейки, уже находится в коллекции, то метод ничего не добавляет и возвращает её индекс.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Создает новую серию диаграммы из [`IChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcellcollection) и добавляет её в коллекцию.

### Возвращаемое значение

Добавленная серия диаграммы или серия, уже находящаяся в коллекции.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcellcollection) | Ячейки, содержащие имена серий. |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип, задающий тип серии |

### Замечания

Если серия диаграммы, созданная из той же ячейки, уже находится в коллекции, то метод ничего не добавляет и возвращает её индекс.


## add(self, name, type) {#str-charttype}
Создает новую серию диаграммы из значения и добавляет её в коллекцию.

### Возвращаемое значение

Добавленная серия диаграммы.



```python
def add(self, name, type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| name | **str** | Имя серии. |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип, задающий тип серии |



### См. также
* перечисление [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype)
* класс [`IChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcellcollection)
* класс [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell)
* класс [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries)
* класс [`IChartSeriesCollection`](/slides/python-net/ru/aspose.slides.charts/ichartseriescollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)