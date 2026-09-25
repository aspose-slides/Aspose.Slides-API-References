---
title: contains method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Определяет, находится ли указанная точка внутри данного прямоугольника.

### Возвращаемое значение

`True` если точка находится внутри данного прямоугольника; в противном случае `False`.



```python
def contains(self, point):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ru/aspose.slides/pointf) | Точка для проверки. Принимается любой объект с атрибутами `x` и `y`. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **TypeError** | Неверное количество аргументов. |


## contains(self, rect) {#rectanglef}
Определяет, полностью ли прямоугольный регион, представленный `rect`, содержится внутри данного прямоугольника.

### Возвращаемое значение

`True` если прямоугольный регион, представленный `rect`, полностью содержится внутри данного прямоугольника; в противном случае `False`.



```python
def contains(self, rect):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef) | Прямоугольник для проверки. Принимается любой объект с атрибутами `x`, `y`, `width` и `height`. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **TypeError** | Неверное количество аргументов. |


## contains(self, x, y) {#float-float}
Определяет, находится ли указанная точка внутри данного прямоугольника.

### Возвращаемое значение

`True` если точка, определённая `x` и `y`, находится внутри данного прямоугольника; в противном случае `False`.



```python
def contains(self, x, y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x проверяемой точки. |
| y | **float** | Координата y проверяемой точки. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **TypeError** | Неверное количество аргументов. |



### См. также
* класс [`PointF`](/slides/python-net/ru/aspose.slides/pointf)
* класс [`RectangleF`](/slides/python-net/ru/aspose.slides/rectanglef)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)