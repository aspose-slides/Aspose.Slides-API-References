---
title: align_shapes method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Ändert die Platzierung aller Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie
            aus oder richtet sie relativ zueinander aus.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/de/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide) | Parent slide. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Ändert die Platzierung aller Formen innerhalb der Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie
            aus oder richtet sie relativ zueinander aus.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/de/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape) | Parent group shape. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Ändert die Platzierung ausgewählter Formen auf der Folie. Richtet Formen an den Rändern oder am Rand der Folie
            aus oder richtet sie relativ zueinander aus.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/de/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide) | Parent slide. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Ändert die Platzierung ausgewählter Formen innerhalb der Gruppierung. Richtet Formen an den Rändern oder am Rand der Folie
            aus oder richtet sie relativ zueinander aus.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/de/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape) | Parent group shape. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |

### Siehe auch
* Klasse [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide)
* Klasse [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape)
* Aufzählung [`ShapesAlignmentType`](/slides/python-net/de/aspose.slides/shapesalignmenttype)
* Klasse [`SlideUtil`](/slides/python-net/de/aspose.slides.util/slideutil)
* Modul [`aspose.slides.util`](/slides/python-net/de/aspose.slides.util)
* Bibliothek [`Aspose.Slides`](/slides/python-net)