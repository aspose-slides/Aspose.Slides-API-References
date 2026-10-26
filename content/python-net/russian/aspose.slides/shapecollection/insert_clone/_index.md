---
title: insert_clone method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. Клонированная фигура сохраняет позицию и размер оригинала.

### Возвращаемое значение

Новое созданное [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой (начиная с нуля) индекс, по которому вставляется клонированная фигура. |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Объект [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. Новая фигура сохраняет ширину и высоту `source_shape`.

### Возвращаемое значение

Новое созданное [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой (начиная с нуля) индекс, по которому вставляется клонированная фигура. |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Объект [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |
| x | **float** | Координата x рамки клонированной фигуры, в пунктах. |
| y | **float** | Координата y рамки клонированной фигуры, в пунктах. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Новое созданное [`IShape`](/slides/python-net/ru/aspose.slides/ishape).



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой (начиная с нуля) индекс, по которому вставляется клонированная фигура. |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | Объект [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |
| x | **float** | Координата x рамки клонированной фигуры, в пунктах. |
| y | **float** | Координата y рамки клонированной фигуры, в пунктах. |
| width | **float** | Ширина рамки клонированной фигуры, в пунктах. |
| height | **float** | Высота рамки клонированной фигуры, в пунктах. |



### См. также
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)