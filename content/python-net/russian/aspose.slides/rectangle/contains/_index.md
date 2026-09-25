---
title: contains method
second_title: Aspose.Slides для Python через .NET: справочник API
description: 
type: docs
url: /ru/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Определяет, находится ли указанный пункт внутри этого прямоугольника.

### Возвращаемое значение

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/ru/aspose.slides/point) | Точка для проверки. Принимается любой объект с атрибутами `x` и `y`. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, rect) {#rectangle}
Определяет, полностью ли прямоугольная область, представленная `rect`, содержится внутри этого прямоугольника.

### Возвращаемое значение

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/ru/aspose.slides/rectangle) | Прямоугольник для проверки. Принимается любой объект с атрибутами `x`, `y`, `width` и `height`. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, x, y) {#int-int}
Определяет, находится ли указанный пункт внутри этого прямоугольника.

### Возвращаемое значение

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **int** | Координата x проверяемого пункта. |
| y | **int** | Координата y проверяемого пункта. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **TypeError** | Wrong number of arguments. |



### См. также
* класс [`Point`](/slides/python-net/ru/aspose.slides/point)
* класс [`Rectangle`](/slides/python-net/ru/aspose.slides/rectangle)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)