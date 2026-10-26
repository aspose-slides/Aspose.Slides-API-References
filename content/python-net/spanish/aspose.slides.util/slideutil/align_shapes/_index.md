---
title: align_shapes method
second_title: Referencia de la API Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Cambia la posición de todas las formas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva
            o las alinea entre sí.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/es/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide) | Parent slide. |


## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Cambia la posición de todas las formas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva
            o las alinea entre sí.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/es/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape) | Parent group shape. |


## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Cambia la posición de las formas seleccionadas en la diapositiva. Alinea las formas a los márgenes o al borde de la diapositiva
             o las alinea entre sí.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/es/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide) | Parent slide. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |


## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Cambia la posición de las formas seleccionadas dentro del grupo de formas. Alinea las formas a los márgenes o al borde de la diapositiva
            o las alinea entre sí.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/es/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape) | Parent group shape. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |



### Ver también
* clase [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide)
* clase [`IGroupShape`](/slides/python-net/es/aspose.slides/igroupshape)
* enumeración [`ShapesAlignmentType`](/slides/python-net/es/aspose.slides/shapesalignmenttype)
* clase [`SlideUtil`](/slides/python-net/es/aspose.slides.util/slideutil)
* módulo [`aspose.slides.util`](/slides/python-net/es/aspose.slides.util)
* biblioteca [`Aspose.Slides`](/slides/python-net)