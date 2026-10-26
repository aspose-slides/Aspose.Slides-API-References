---
title: align_shapes method
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Altera a posição de todas as formas no slide. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pt/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide) | Parent slide. |


## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Altera a posição de todas as formas dentro do grupo de formas. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pt/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape) | Parent group shape. |


## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Altera a posição das formas selecionadas no slide. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pt/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide) | Parent slide. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |


## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Altera a posição das formas selecionadas dentro do grupo de formas. Alinha as formas às margens ou à borda do slide ou alinha-as entre si.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| Parâmetro | Tipo | Descrição |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pt/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape) | Parent group shape. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |



### Veja Também
* classe [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide)
* classe [`IGroupShape`](/slides/python-net/pt/aspose.slides/igroupshape)
* enumeração [`ShapesAlignmentType`](/slides/python-net/pt/aspose.slides/shapesalignmenttype)
* classe [`SlideUtil`](/slides/python-net/pt/aspose.slides.util/slideutil)
* módulo [`aspose.slides.util`](/slides/python-net/pt/aspose.slides.util)
* biblioteca [`Aspose.Slides`](/slides/python-net)