---
title: align_shapes method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Mengubah penempatan semua bentuk pada slide. Menyelaraskan bentuk ke margin atau tepi slide
            atau menyelaraskannya secara relatif satu sama lain.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/id/aspose.slides/shapesalignmenttype) | Menentukan jenis penyelarasan yang akan diterapkan. |
| align_to_slide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| slide | [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide) | Slide induk. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Mengubah penempatan semua bentuk dalam group shape. Menyelaraskan bentuk ke margin atau tepi slide
            atau menyelaraskannya secara relatif satu sama lain.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/id/aspose.slides/shapesalignmenttype) | Menentukan jenis penyelarasan yang akan diterapkan. |
| align_to_slide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| group_shape | [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape) | Group shape induk. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Mengubah penempatan bentuk yang dipilih pada slide. Menyelaraskan bentuk ke margin atau tepi slide
             atau menyelaraskannya secara relatif satu sama lain.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/id/aspose.slides/shapesalignmenttype) | Menentukan jenis penyelarasan yang akan diterapkan. |
| align_to_slide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| slide | [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide) | Slide induk. |
| shape_indexes | **List[int]** | Indeks bentuk yang akan diselaraskan. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Mengubah penempatan bentuk yang dipilih dalam group shape. Menyelaraskan bentuk ke margin atau tepi slide
            atau menyelaraskannya secara relatif satu sama lain.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/id/aspose.slides/shapesalignmenttype) | Menentukan jenis penyelarasan yang akan diterapkan. |
| align_to_slide | **bool** | Jika true, bentuk akan diselaraskan relatif terhadap tepi slide. |
| group_shape | [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape) | Group shape induk. |
| shape_indexes | **List[int]** | Indeks bentuk yang akan diselaraskan. |

### Lihat Juga
* kelas [`IBaseSlide`](/slides/python-net/id/aspose.slides/ibaseslide)
* kelas [`IGroupShape`](/slides/python-net/id/aspose.slides/igroupshape)
* enumerasi [`ShapesAlignmentType`](/slides/python-net/id/aspose.slides/shapesalignmenttype)
* kelas [`SlideUtil`](/slides/python-net/id/aspose.slides.util/slideutil)
* modul [`aspose.slides.util`](/slides/python-net/id/aspose.slides.util)
* pustaka [`Aspose.Slides`](/slides/python-net)