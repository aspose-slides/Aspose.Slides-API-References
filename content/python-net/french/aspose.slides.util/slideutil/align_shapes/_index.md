---
title: align_shapes method
second_title: Aspose.Slides pour Python via la référence d'API .NET
description: 
type: docs
url: /fr/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Modifie le placement de toutes les formes sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive, ou les aligne les unes par rapport aux autres.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fr/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide) | Parent slide. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Modifie le placement de toutes les formes au sein du groupe de formes. Aligne les formes aux marges ou au bord de la diapositive, ou les aligne les unes par rapport aux autres.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fr/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape) | Parent group shape. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Modifie le placement des formes sélectionnées sur la diapositive. Aligne les formes aux marges ou au bord de la diapositive, ou les aligne les unes par rapport aux autres.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fr/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide) | Parent slide. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Modifie le placement des formes sélectionnées au sein du groupe de formes. Aligne les formes aux marges ou au bord de la diapositive, ou les aligne les unes par rapport aux autres.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fr/aspose.slides/shapesalignmenttype) | Determines which type of alignment will be applied. |
| align_to_slide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| group_shape | [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape) | Parent group shape. |
| shape_indexes | **List[int]** | Indexes of shapes to be aligned. |

### Voir aussi
* classe [`IBaseSlide`](/slides/python-net/fr/aspose.slides/ibaseslide)
* classe [`IGroupShape`](/slides/python-net/fr/aspose.slides/igroupshape)
* énumération [`ShapesAlignmentType`](/slides/python-net/fr/aspose.slides/shapesalignmenttype)
* classe [`SlideUtil`](/slides/python-net/fr/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/fr/aspose.slides.util)
* bibliothèque [`Aspose.Slides`](/slides/python-net)