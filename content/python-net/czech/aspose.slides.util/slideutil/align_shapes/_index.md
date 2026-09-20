---
title: align_shapes method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo k okraji snímku
nebo je zarovnává relativně k sobě navzájem.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/cs/aspose.slides/shapesalignmenttype) | Určuje, který typ zarovnání bude použit. |
| align_to_slide | **bool** | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| slide | [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide) | Nadřazený snímek. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Mění umístění všech tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k okraji snímku
nebo je zarovnává relativně k sobě navzájem.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/cs/aspose.slides/shapesalignmenttype) | Určuje, který typ zarovnání bude použit. |
| align_to_slide | **bool** | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| group_shape | [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape) | Nadřazený skupinový tvar. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Mění umístění vybraných tvarů na snímku. Zarovnává tvary k okrajům nebo k okraji snímku
nebo je zarovnává relativně k sobě navzájem.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/cs/aspose.slides/shapesalignmenttype) | Určuje, který typ zarovnání bude použit. |
| align_to_slide | **bool** | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| slide | [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide) | Nadřazený snímek. |
| shape_indexes | **List[int]** | Indexy tvarů, které mají být zarovnány. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Mění umístění vybraných tvarů ve skupinovém tvaru. Zarovnává tvary k okrajům nebo k okraji snímku
nebo je zarovnává relativně k sobě navzájem.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/cs/aspose.slides/shapesalignmenttype) | Určuje, který typ zarovnání bude použit. |
| align_to_slide | **bool** | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| group_shape | [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape) | Nadřazený skupinový tvar. |
| shape_indexes | **List[int]** | Indexy tvarů, které mají být zarovnány. |

### Viz také
* třída [`IBaseSlide`](/slides/python-net/cs/aspose.slides/ibaseslide)
* třída [`IGroupShape`](/slides/python-net/cs/aspose.slides/igroupshape)
* enumerace [`ShapesAlignmentType`](/slides/python-net/cs/aspose.slides/shapesalignmenttype)
* třída [`SlideUtil`](/slides/python-net/cs/aspose.slides.util/slideutil)
* modul [`aspose.slides.util`](/slides/python-net/cs/aspose.slides.util)
* knihovna [`Aspose.Slides`](/slides/python-net)