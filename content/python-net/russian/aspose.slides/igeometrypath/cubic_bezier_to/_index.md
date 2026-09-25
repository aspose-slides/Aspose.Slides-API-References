---
title: cubic_bezier_to method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Добавляет кубическую кривую Безье в конец пути


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Первая точка направления |
| point2 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Вторая точка направления |
| point3 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Конечная точка |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Добавляет кубическую кривую Безье в указанное место пути


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Первая точка направления |
| point2 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Вторая точка направления |
| point3 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Конечная точка |
| index | **int** | Индекс сегмента в PathData |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Индекс сегмента выходит за пределы диапазона PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Добавляет кубическую кривую Безье в конец пути


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x1 | **float** | Координата X первой точки направления |
| y1 | **float** | Координата Y первой точки направления |
| x2 | **float** | Координата X второй точки направления |
| y2 | **float** | Координата Y второй точки направления |
| x3 | **float** | Координата X конечной точки |
| y3 | **float** | Координата Y конечной точки |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Добавляет кубическую кривую Безье в указанное место пути


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x1 | **float** | Координата X первой точки направления |
| y1 | **float** | Координата Y первой точки направления |
| x2 | **float** | Координата X второй точки направления |
| y2 | **float** | Координата Y второй точки направления |
| x3 | **float** | Координата X конечной точки |
| y3 | **float** | Координата Y конечной точки |
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