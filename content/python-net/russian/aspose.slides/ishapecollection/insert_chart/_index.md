---
title: insert_chart method
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
Создает новую диаграмму, инициализирует её образцовыми данными серии и настройками и вставляет её в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart).

```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип создаваемой диаграммы. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина новой диаграммы в пунктах. |
| height | **float** | Высота новой диаграммы в пунктах. |
| index | **int** | Нулевая базовая позиция, по которой вставляется новая диаграмма в коллекцию фигур. |

## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
Создает новую диаграмму, инициализирует её образцовыми данными серии и настройками и вставляет её в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart).

```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype) | Тип создаваемой диаграммы. |
| x | **float** | Координата x новой диаграммы в пунктах. |
| y | **float** | Координата y новой диаграммы в пунктах. |
| width | **float** | Ширина новой диаграммы в пунктах. |
| height | **float** | Высота новой диаграммы в пунктах. |
| index | **int** | Нулевая базовая позиция, по которой вставляется новая диаграмма в коллекцию фигур. |
| init_with_sample | **bool** | True — инициализировать новую диаграмму образцовыми данными серии и настройками; <br/><br/>false — создать диаграмму без серий и только с минимальными настройками, что ускоряет создание. |

### См. также
* перечисление [`ChartType`](/slides/python-net/ru/aspose.slides.charts/charttype)
* класс [`IChart`](/slides/python-net/ru/aspose.slides.charts/ichart)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)