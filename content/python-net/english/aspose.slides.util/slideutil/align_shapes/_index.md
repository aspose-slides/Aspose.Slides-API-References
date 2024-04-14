---
title: align_shapes method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.util/slideutil/align_shapes/
weight: 10
---


## align_shapes {#shapesalignmenttype-bool-ishapecollection}
Changes the placement of all shapes in the collection. Aligns shapes to the margins or the edge of the slide
            or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, shapes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | ShapesAlignmentType | Determines which type of alignment will be applied. |
| align_to_slide | bool | If true, shapes will be aligned relative to the slide edges |
| shapes | IShapeCollection | Shapes collection to be aligned |



## align_shapes {#shapesalignmenttype-bool-ibaseslide}
Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide
            or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | ShapesAlignmentType | Determines which type of alignment will be applied. |
| align_to_slide | bool | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Parent slide. |



## align_shapes {#shapesalignmenttype-bool-igroupshape}
Changes the placement of all shapes within group shape. Aligns shapes to the margins or the edge of the slide
            or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, group_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | ShapesAlignmentType | Determines which type of alignment will be applied. |
| align_to_slide | bool | If true, shapes will be aligned relative to the slide edges. |
| group_shape | IGroupShape | Parent group shape. |



## align_shapes {#shapesalignmenttype-bool-ibaseslide-listint}
Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide
             or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | ShapesAlignmentType | Determines which type of alignment will be applied. |
| align_to_slide | bool | If true, shapes will be aligned relative to the slide edges. |
| slide | IBaseSlide | Parent slide. |
| shape_indexes | List[int] | Indexes of shapes to be aligned. |



## align_shapes {#shapesalignmenttype-bool-igroupshape-listint}
Changes the placement of selected shapes within group shape. Aligns shapes to the margins or the edge of the slide
            or align them relative to each other.


```python
def align_shapes(self, alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| alignment_type | ShapesAlignmentType | Determines which type of alignment will be applied. |
| align_to_slide | bool | If true, shapes will be aligned relative to the slide edges. |
| group_shape | IGroupShape | Parent group shape. |
| shape_indexes | List[int] | Indexes of shapes to be aligned. |



