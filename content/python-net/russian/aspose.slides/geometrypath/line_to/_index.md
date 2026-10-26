---
title: line_to method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Добавляет линию в конец пути


```python
def line_to(self, point):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Конечная точка линии |


## line_to(self, x, y) {#float-float}
Добавляет линию в конец пути


```python
def line_to(self, x, y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата X конечной точки линии |
| y | **float** | Координата Y конечной точки линии |


## line_to(self, point, index) {#asposeslidespointf-int}
Добавляет линию в указанное место пути


```python
def line_to(self, point, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Конечная точка |
| index | **int** | Индекс сегмента в PathData |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс сегмента выходит за пределы диапазона PathData |


## line_to(self, x, y, index) {#float-float-int}
Добавляет линию в указанное место пути


```python
def line_to(self, x, y, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата X точки |
| y | **float** | Координата Y точки |
| index | **int** | Индекс сегмента в PathData |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс сегмента выходит за пределы диапазона PathData |



### См. также
* класс [`GeometryPath`](/slides/python-net/ru/aspose.slides/geometrypath)
* класс [`PointF`](/slides/python-net/ru/aspose.slides/pointf)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)