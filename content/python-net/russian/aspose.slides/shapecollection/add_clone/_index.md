---
title: add_clone method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Создает копию указанной фигуры и добавляет её в конец коллекции фигур.
            Клонированная фигура сохраняет позицию и размер оригинала.

### Returns

Недавно созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Создает копию указанной фигуры и добавляет её в конец коллекции фигур.
            Новая фигура сохраняет ширину и высоту `source_shape`.

### Returns

Недавно созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Фигура для клонирования. |
| x | **float** | Координата x кадра новой фигуры, в пунктах. |
| y | **float** | Координата y кадра новой фигуры, в пунктах. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Создает копию указанной фигуры и добавляет её в конец коллекции фигур.

### Returns

Недавно созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Фигура для клонирования. |
| x | **float** | Координата x кадра новой фигуры, в пунктах. |
| y | **float** | Координата y кадра новой фигуры, в пунктах. |
| width | **float** | Ширина кадра новой фигуры, в пунктах. |
| height | **float** | Высота кадра новой фигуры, в пунктах. |



### См. также
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)