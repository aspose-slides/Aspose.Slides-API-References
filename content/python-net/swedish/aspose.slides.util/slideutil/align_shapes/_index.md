---
title: align_shapes method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Ändrar placeringen av alla former på bilden. Justerar formerna till marginalerna eller bildens kant
            eller justerar dem i förhållande till varandra.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/sv/aspose.slides/shapesalignmenttype) | Bestämmer vilken typ av justering som ska tillämpas. |
| align_to_slide | **bool** | Om true, kommer former att justeras i förhållande till bildens kanter. |
| slide | [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide) | Föräldrabild. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Ändrar placeringen av alla former inom gruppformen. Justerar formerna till marginalerna eller bildens kant
            eller justerar dem i förhållande till varandra.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/sv/aspose.slides/shapesalignmenttype) | Bestämmer vilken typ av justering som ska tillämpas. |
| align_to_slide | **bool** | Om true, kommer former att justeras i förhållande till bildens kanter. |
| group_shape | [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape) | Föräldragruppform. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Ändrar placeringen av valda former på bilden. Justerar formerna till marginalerna eller bildens kant
             eller justerar dem i förhållande till varandra.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/sv/aspose.slides/shapesalignmenttype) | Bestämmer vilken typ av justering som ska tillämpas. |
| align_to_slide | **bool** | Om true, kommer former att justeras i förhållande till bildens kanter. |
| slide | [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide) | Föräldrabild. |
| shape_indexes | **List[int]** | Index för former som ska justeras. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Ändrar placeringen av valda former inom gruppformen. Justerar formerna till marginalerna eller bildens kant
            eller justerar dem i förhållande till varandra.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/sv/aspose.slides/shapesalignmenttype) | Bestämmer vilken typ av justering som ska tillämpas. |
| align_to_slide | **bool** | Om true, kommer former att justeras i förhållande till bildens kanter. |
| group_shape | [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape) | Föräldragruppform. |
| shape_indexes | **List[int]** | Index för former som ska justeras. |

### Se även
* class [`IBaseSlide`](/slides/python-net/sv/aspose.slides/ibaseslide)
* class [`IGroupShape`](/slides/python-net/sv/aspose.slides/igroupshape)
* enumeration [`ShapesAlignmentType`](/slides/python-net/sv/aspose.slides/shapesalignmenttype)
* class [`SlideUtil`](/slides/python-net/sv/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/sv/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)