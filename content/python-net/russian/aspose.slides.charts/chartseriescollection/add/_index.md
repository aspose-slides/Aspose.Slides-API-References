---
title: add method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Создаёт новую серию диаграммы и добавляет её в коллекцию.

### Возвращаемое значение
Новая серия диаграммы.



```python
def add(self, type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Type of series |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Создаёт новую серию диаграммы из [`ChartDataCell`](/slides/python-net/ru/aspose.slides.charts/chartdatacell) и добавляет её в коллекцию.

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

### Примечания
Если серия диаграммы, созданная из той же ячейки, уже находится в коллекции, метод ничего не добавляет и возвращает её индекс.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Создаёт новую серию диаграммы из [`ChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/chartcellcollection) и добавляет её в коллекцию.

### Возвращаемое значение
Добавленная серия диаграммы или серия, уже находящаяся в коллекции.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcellcollection) | Ячейки, содержащие имя серии. |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип, задающий тип серии |

### Примечания
Если серия диаграммы, созданная из той же ячейки, уже находится в коллекции, метод ничего не добавляет и возвращает её индекс.


## add(self, name, type) {#str-charttype}
Создаёт новую серию диаграммы из значения и добавляет её в коллекцию.

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
* класс [`ChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/chartcellcollection)
* класс [`ChartDataCell`](/slides/python-net/ru/aspose.slides.charts/chartdatacell)
* класс [`ChartSeriesCollection`](/slides/python-net/ru/aspose.slides.charts/chartseriescollection)
* перечисление [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype)
* класс [`IChartCellCollection`](/slides/python-net/ru/aspose.slides.charts/ichartcellcollection)
* класс [`IChartDataCell`](/slides/python-net/ru/aspose.slides.charts/ichartdatacell)
* класс [`IChartSeries`](/slides/python-net/ru/aspose.slides.charts/ichartseries)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)