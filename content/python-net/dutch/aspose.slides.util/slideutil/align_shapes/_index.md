---
title: align_shapes method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Wijzigt de plaatsing van alle vormen op de dia. Uitlijnt vormen op de marges of de rand van de dia
            of uitlijnt ze ten opzichte van elkaar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/nl/aspose.slides/shapesalignmenttype) | Bepaalt welk type uitlijning zal worden toegepast. |
| align_to_slide | **bool** | Als true, worden vormen ten opzichte van de randen van de dia uitgelijnd. |
| slide | [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide) | Bovenliggende dia. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Wijzigt de plaatsing van alle vormen binnen groepvorm. Uitlijnt vormen op de marges of de rand van de dia
            of uitlijnt ze ten opzichte van elkaar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/nl/aspose.slides/shapesalignmenttype) | Bepaalt welk type uitlijning zal worden toegepast. |
| align_to_slide | **bool** | Als true, worden vormen ten opzichte van de randen van de dia uitgelijnd. |
| group_shape | [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape) | Bovenliggende groepvorm. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Wijzigt de plaatsing van geselecteerde vormen op de dia. Uitlijnt vormen op de marges of de rand van de dia
             of uitlijnt ze ten opzichte van elkaar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/nl/aspose.slides/shapesalignmenttype) | Bepaalt welk type uitlijning zal worden toegepast. |
| align_to_slide | **bool** | Als true, worden vormen ten opzichte van de randen van de dia uitgelijnd. |
| slide | [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide) | Bovenliggende dia. |
| shape_indexes | **List[int]** | Indexen van vormen die moeten worden uitgelijnd. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Wijzigt de plaatsing van geselecteerde vormen binnen groepvorm. Uitlijnt vormen op de marges of de rand van de dia
            of uitlijnt ze ten opzichte van elkaar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/nl/aspose.slides/shapesalignmenttype) | Bepaalt welk type uitlijning zal worden toegepast. |
| align_to_slide | **bool** | Als true, worden vormen ten opzichte van de randen van de dia uitgelijnd. |
| group_shape | [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape) | Bovenliggende groepvorm. |
| shape_indexes | **List[int]** | Indexen van vormen die moeten worden uitgelijnd. |

### Zie ook
* klasse [`IBaseSlide`](/slides/python-net/nl/aspose.slides/ibaseslide)
* klasse [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape)
* enumeratie [`ShapesAlignmentType`](/slides/python-net/nl/aspose.slides/shapesalignmenttype)
* klasse [`SlideUtil`](/slides/python-net/nl/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/nl/aspose.slides.util)
* bibliotheek [`Aspose.Slides`](/slides/python-net)