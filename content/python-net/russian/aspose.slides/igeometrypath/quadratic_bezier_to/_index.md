---
title: quadratic_bezier_to method
second_title: Aspose.Slides для Python через .NET – справочник API
description: 
type: docs
url: /ru/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Добавляет квадратичную кривую Безье в конец пути


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Точка направления |
| point2 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Конечная точка |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Добавляет квадратичную кривую Безье в указанное место пути


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Точка направления |
| point2 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Конечная точка |
| index | **int** | Индекс сегмента в PathData |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс сегмента выходит за пределы диапазона PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Добавляет квадратичную кривую Безье в конец пути


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x1 | **float** | Координата X точки направления |
| y1 | **float** | Координата Y точки направления |
| x2 | **float** | Координата X конечной точки |
| y2 | **float** | Координата Y конечной точки |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Добавляет квадратичную кривую Безье в указанное место пути


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x1 | **float** | Координата X точки направления |
| y1 | **float** | Координата Y точки направления |
| x2 | **float** | Координата X конечной точки |
| y2 | **float** | Координата Y конечной точки |
| index | **int** | Индекс сегмента в PathData |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс сегмента выходит за пределы диапазона PathData |



### См. также
* класс [`IGeometryPath`](/slides/python-net/ru/aspose.slides/igeometrypath)
* класс [`PointF`](/slides/python-net/ru/aspose.slides/pointf)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)