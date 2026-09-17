---
title: insert_clone method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Создает копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.
Склонированная фигура сохраняет положение и размер оригинала.

### Возвращаемое значение

Созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевая позиция, в которую вставляется склонированная фигура. |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Создает копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.
Новая фигура сохраняет ширину и высоту `source_shape`.

### Возвращаемое значение

Созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевая позиция, в которую вставляется склонированная фигура. |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |
| x | **float** | Координата x кадра склонированной фигуры в пунктах. |
| y | **float** | Координата y кадра склонированной фигуры в пунктах. |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Создает копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IShape`](/slides/python-net/ru/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевая позиция, в которую вставляется склонированная фигура. |
| source_shape | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) | [`IShape`](/slides/python-net/ru/aspose.slides/ishape) для клонирования. |
| x | **float** | Координата x кадра склонированной фигуры в пунктах. |
| y | **float** | Координата y кадра склонированной фигуры в пунктах. |
| width | **float** | Ширина кадра склонированной фигуры в пунктах. |
| height | **float** | Высота кадра склонированной фигуры в пунктах. |

### См. также
* класс [`IShape`](/slides/python-net/ru/aspose.slides/ishape)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)