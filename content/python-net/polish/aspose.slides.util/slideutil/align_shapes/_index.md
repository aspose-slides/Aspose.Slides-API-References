---
title: align_shapes method
second_title: Aspose.Slides dla Pythona przez .NET – Referencja API
description: 
type: docs
url: /pl/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Zmienia położenie wszystkich kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pl/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide) | Parent slide. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Zmienia położenie wszystkich kształtów w grupie kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pl/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape) | Parent group shape. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Zmienia położenie wybranych kształtów na slajdzie. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pl/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide) | Parent slide. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Zmienia położenie wybranych kształtów w grupie kształtów. Wyrównuje kształty do marginesów lub krawędzi slajdu albo wyrównuje je względem siebie.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/pl/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape) | Parent group shape. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |

### Zobacz także
* klasa [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide)
* klasa [`IGroupShape`](/slides/python-net/pl/aspose.slides/igroupshape)
* enumeracja [`ShapesAlignmentType`](/slides/python-net/pl/aspose.slides/shapesalignmenttype)
* klasa [`SlideUtil`](/slides/python-net/pl/aspose.slides.util/slideutil)
* moduł [`aspose.slides.util`](/slides/python-net/pl/aspose.slides.util)
* biblioteka [`Aspose.Slides`](/slides/python-net)