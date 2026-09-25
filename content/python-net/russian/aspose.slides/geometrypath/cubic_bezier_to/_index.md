---
title: cubic_bezier_to method
second_title: Aspose.Slides для Python через .NET: справочник API
description: 
type: docs
url: /ru/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Добавляет кубическую кривую Безье в конец пути


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | First direction point |
| point2 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Second direction point |
| point3 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | End point |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Добавляет кубическую кривую Безье в указанное место пути


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | First direction point |
| point2 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Second direction point |
| point3 | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | End point |
| index | **int** | Index of segment in PathData |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Добавляет кубическую кривую Безье в конец пути


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Добавляет кубическую кривую Безье в указанное место пути


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x1 | **float** | X coordinate of first direction point |
| y1 | **float** | Y coordinate of first direction point |
| x2 | **float** | X coordinate of second direction point |
| y2 | **float** | Y coordinate of second direction point |
| x3 | **float** | X coordinate of end point |
| y3 | **float** | Y coordinate of end point |
| index | **int** | Index of segment in PathData |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |



### См. также
* класс [`GeometryPath`](/slides/python-net/ru/aspose.slides/geometrypath)
* класс [`PointF`](/slides/python-net/ru/aspose.slides/pointf)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)