---
title: align_shapes method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Изменяет размещение всех фигур на слайде. Выравнивает фигуры по полям или краю слайда,
либо выравнивает их относительно друг друга.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ru/aspose.slides/shapesalignmenttype) | Определяет, какой тип выравнивания будет применён. |
| align_to_slide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | Родительский слайд. |


## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Изменяет размещение всех фигур внутри групповой фигуры. Выравнивает фигуры по полям или краю слайда,
либо выравнивает их относительно друг друга.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ru/aspose.slides/shapesalignmenttype) | Определяет, какой тип выравнивания будет применён. |
| align_to_slide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| group_shape | [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape) | Родительская групповая форма. |


## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Изменяет размещение выбранных фигур на слайде. Выравнивает фигуры по полям или краю слайда,
либо выравнивает их относительно друг друга.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ru/aspose.slides/shapesalignmenttype) | Определяет, какой тип выравнивания будет применён. |
| align_to_slide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| slide | [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide) | Родительский слайд. |
| shape_indexes | **List[int]** | Индексы фигур для выравнивания. |


## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Изменяет размещение выбранных фигур внутри групповой фигуры. Выравнивает фигуры по полям или краю слайда,
либо выравнивает их относительно друг друга.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ru/aspose.slides/shapesalignmenttype) | Определяет, какой тип выравнивания будет применён. |
| align_to_slide | **bool** | Если true, фигуры будут выравнены относительно краёв слайда. |
| group_shape | [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape) | Родительская групповая форма. |
| shape_indexes | **List[int]** | Индексы фигур для выравнивания. |



### См. также
* класс [`IBaseSlide`](/slides/python-net/ru/aspose.slides/ibaseslide)
* класс [`IGroupShape`](/slides/python-net/ru/aspose.slides/igroupshape)
* перечисление [`ShapesAlignmentType`](/slides/python-net/ru/aspose.slides/shapesalignmenttype)
* класс [`SlideUtil`](/slides/python-net/ru/aspose.slides.util/slideutil)
* модуль [`aspose.slides.util`](/slides/python-net/ru/aspose.slides.util)
* библиотека [`Aspose.Slides`](/slides/python-net)