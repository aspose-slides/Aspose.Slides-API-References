---
title: align_shapes method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Modifica la posizione di tutte le forme sulla slide. Allinea le forme ai margini o al bordo della slide o le allinea tra loro.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/it/aspose.slides/shapesalignmenttype) | Determina quale tipo di allineamento verrà applicato. |
| align_to_slide | **bool** | Se vero, le forme saranno allineate rispetto ai bordi della slide. |
| slide | [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide) | Slide principale. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Modifica la posizione di tutte le forme all'interno del gruppo di forme. Allinea le forme ai margini o al bordo della slide o le allinea tra loro.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/it/aspose.slides/shapesalignmenttype) | Determina quale tipo di allineamento verrà applicato. |
| align_to_slide | **bool** | Se vero, le forme saranno allineate rispetto ai bordi della slide. |
| group_shape | [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape) | Forma di gruppo principale. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Modifica la posizione delle forme selezionate sulla slide. Allinea le forme ai margini o al bordo della slide o le allinea tra loro.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/it/aspose.slides/shapesalignmenttype) | Determina quale tipo di allineamento verrà applicato. |
| align_to_slide | **bool** | Se vero, le forme saranno allineate rispetto ai bordi della slide. |
| slide | [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide) | Slide principale. |
| shape_indexes | **List[int]** | Indici delle forme da allineare. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Modifica la posizione delle forme selezionate all'interno del gruppo di forme. Allinea le forme ai margini o al bordo della slide o le allinea tra loro.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/it/aspose.slides/shapesalignmenttype) | Determina quale tipo di allineamento verrà applicato. |
| align_to_slide | **bool** | Se vero, le forme saranno allineate rispetto ai bordi della slide. |
| group_shape | [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape) | Forma di gruppo principale. |
| shape_indexes | **List[int]** | Indici delle forme da allineare. |

### Vedi anche
* classe [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide)
* classe [`IGroupShape`](/slides/python-net/it/aspose.slides/igroupshape)
* enumerazione [`ShapesAlignmentType`](/slides/python-net/it/aspose.slides/shapesalignmenttype)
* classe [`SlideUtil`](/slides/python-net/it/aspose.slides.util/slideutil)
* modulo [`aspose.slides.util`](/slides/python-net/it/aspose.slides.util)
* libreria [`Aspose.Slides`](/slides/python-net)