---
title: add_chart method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
Создает новую диаграмму, инициализирует её образцами данных серии и настройками и добавляет её в конец коллекции фигур.

### Возвращаемое значение

Новое созданное [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип диаграммы для добавления. |
| x | **float** | Координата x новой диаграммы, в пунктах. |
| y | **float** | Координата y новой диаграммы, в пунктах. |
| width | **float** | Ширина диаграммы, в пунктах. |
| height | **float** | Высота диаграммы, в пунктах. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
Создает новую диаграмму, инициализирует её образцами данных серии и настройками и добавляет её в конец коллекции фигур.

### Возвращаемое значение

Новое созданное [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип диаграммы для добавления. |
| x | **float** | Координата x новой диаграммы, в пунктах. |
| y | **float** | Координата y новой диаграммы, в пунктах. |
| width | **float** | Ширина диаграммы, в пунктах. |
| height | **float** | Высота диаграммы, в пунктах. |
| init_with_sample | **bool** | True, чтобы инициализировать новую диаграмму образцами данных серии и настройками; <br/><br/>            false, чтобы создать диаграмму без серий и только с минимальными настройками, что ускоряет создание. |



### См. также
* перечисление [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype)
* класс [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)