---
title: add_clone method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.
            Клонированная фигура сохраняет позицию и размер оригинала.

### Возвращаемое значение

Созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.
            Новая фигура сохраняет ширину и высоту `source_shape`.

### Возвращаемое значение

Созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |
| x | **float** | Координата x кадра клонированной фигуры в пунктах. |
| y | **float** | Координата y кадра клонированной фигуры в пунктах. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.

### Возвращаемое значение

Созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Фигура для клонирования. |
| x | **float** | Координата x кадра клонированной фигуры в пунктах. |
| y | **float** | Координата y кадра клонированной фигуры в пунктах. |
| width | **float** | Ширина кадра клонированной фигуры в пунктах. |
| height | **float** | Высота кадра клонированной фигуры в пунктах. |



### См. также
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)