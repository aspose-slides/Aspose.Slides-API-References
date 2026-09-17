---
title: insert_chart method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Создает новый график, инициализирует его образцовыми данными серии и настройками и вставляет в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Недавно созданный [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип графика для создания. |
| x | **float** | Координата x нового графика, в пунктах. |
| y | **float** | Координата y нового графика, в пунктах. |
| width | **float** | Ширина нового графика, в пунктах. |
| height | **float** | Высота нового графика, в пунктах. |
| index | **int** | Нулевой индекс, по которому необходимо вставить новый график в коллекцию фигур. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Создает новый график, инициализирует его образцовыми данными серии и настройками и вставляет в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Недавно созданный [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип графика для создания. |
| x | **float** | Координата x нового графика, в пунктах. |
| y | **float** | Координата y нового графика, в пунктах. |
| width | **float** | Ширина нового графика, в пунктах. |
| height | **float** | Высота нового графика, в пунктах. |
| index | **int** | Нулевой индекс, по которому необходимо вставить новый график в коллекцию фигур. |
| init_with_sample | **bool** | True для инициализации нового графика образцовыми данными серии и настройками; <br/><br/>            false для создания графика без серий и только с минимальными настройками, что ускоряет процесс создания. |



### См. также
* перечисление [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype)
* класс [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)