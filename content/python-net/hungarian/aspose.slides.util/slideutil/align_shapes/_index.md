---
title: align_shapes method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Módosítja az összes alakzat elhelyezését a dián. Igazítja az alakzatokat a margókhoz vagy a dia széléhez,
vagy egymáshoz viszonyítva igazítja őket.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hu/aspose.slides/shapesalignmenttype) | Meghatározza, hogy melyik igazítási típus lesz alkalmazva. |
| align_to_slide | **bool** | Ha true, a formák a dia széleihez lesznek igazítva. |
| slide | [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide) | Szülő dia. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Módosítja az összes alakzat elhelyezését a csoport alakzaton belül. Igazítja az alakzatokat a margókhoz vagy a dia széléhez,
vagy egymáshoz viszonyítva igazítja őket.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hu/aspose.slides/shapesalignmenttype) | Meghatározza, hogy melyik igazítási típus lesz alkalmazva. |
| align_to_slide | **bool** | Ha true, a formák a dia széleihez lesznek igazítva. |
| group_shape | [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape) | Szülő csoport alakzat. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Kiválasztott alakzatok elhelyezését módosítja a dián. Igazítja az alakzatokat a margókhoz vagy a dia széléhez,
vagy egymáshoz viszonyítva igazítja őket.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hu/aspose.slides/shapesalignmenttype) | Meghatározza, hogy melyik igazítási típus lesz alkalmazva. |
| align_to_slide | **bool** | Ha true, a formák a dia széleihez lesznek igazítva. |
| slide | [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide) | Szülő dia. |
| shape_indexes | **List[int]** | Az igazítandó alakzatok indexei. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Kiválasztott alakzatok elhelyezését módosítja a csoport alakzaton belül. Igazítja az alakzatokat a margókhoz vagy a dia széléhez,
vagy egymáshoz viszonyítva igazítja őket.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/hu/aspose.slides/shapesalignmenttype) | Meghatározza, hogy melyik igazítási típus lesz alkalmazva. |
| align_to_slide | **bool** | Ha true, a formák a dia széleihez lesznek igazítva. |
| group_shape | [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape) | Szülő csoport alakzat. |
| shape_indexes | **List[int]** | Az igazítandó alakzatok indexei. |

### Lásd még
* osztály [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide)
* osztály [`IGroupShape`](/slides/python-net/hu/aspose.slides/igroupshape)
* enumeráció [`ShapesAlignmentType`](/slides/python-net/hu/aspose.slides/shapesalignmenttype)
* osztály [`SlideUtil`](/slides/python-net/hu/aspose.slides.util/slideutil)
* modul [`aspose.slides.util`](/slides/python-net/hu/aspose.slides.util)
* könyvtár [`Aspose.Slides`](/slides/python-net)