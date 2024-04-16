---
title: align_shapes method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.util/slideutil/align_shapes/
weight: 10
---


## align_shapes {#shapesalignmenttype-bool-ibaseslide}
Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
            or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide) | Parent slide. |


## align_shapes {#shapesalignmenttype-bool-igroupshape}
Changes the placement of all shapes within group shape. Aligns shapes to the margins or the edge of the slide
            or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, group_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape) | Parent group shape. |


## align_shapes {#shapesalignmenttype-bool-ibaseslide-listint}
Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
             or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide) | Parent slide. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |


## align_shapes {#shapesalignmenttype-bool-igroupshape-listint}
Changes the placement of selected shapes within group shape. Aligns shapes to the margins or the edge of the slide
            or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape) | Parent group shape. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |



### See Also
* class [`IBaseSlide`](/slides/python-net/aspose.slides/ibaseslide)
* class [`IGroupShape`](/slides/python-net/aspose.slides/igroupshape)
* enumeration [`ShapesAlignmentType`](/slides/python-net/aspose.slides/shapesalignmenttype)
* class [`SlideUtil`](/slides/python-net/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)

