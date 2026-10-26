---
title: align_shapes method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
Slayttaki tüm şekillerin konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar
            ya da birbirlerine göre hizalar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/tr/aspose.slides/shapesalignmenttype) | Hangi hizalama tipinin uygulanacağını belirler. |
| align_to_slide | **bool** | **true** ise şekiller slayt kenarlarına göre hizalanır. |
| slide | [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide) | Üst slayt. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
Grup şekli içindeki tüm şekillerin konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar
            ya da birbirlerine göre hizalar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/tr/aspose.slides/shapesalignmenttype) | Hangi hizalama tipinin uygulanacağını belirler. |
| align_to_slide | **bool** | **true** ise şekiller slayt kenarlarına göre hizalanır. |
| group_shape | [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape) | Üst grup şekli. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
Slayttaki seçili şekillerin konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar
             ya da birbirlerine göre hizalar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/tr/aspose.slides/shapesalignmenttype) | Hangi hizalama tipinin uygulanacağını belirler. |
| align_to_slide | **bool** | **true** ise şekiller slayt kenarlarına göre hizalanır. |
| slide | [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide) | Üst slayt. |
| shape_indexes | **List[int]** | Hizalanacak şekillerin indeksleri. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
Grup şekli içindeki seçili şekillerin konumunu değiştirir. Şekilleri kenarlara veya slayt kenarına hizalar
            ya da birbirlerine göre hizalar.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/tr/aspose.slides/shapesalignmenttype) | Hangi hizalama tipinin uygulanacağını belirler. |
| align_to_slide | **bool** | **true** ise şekiller slayt kenarlarına göre hizalanır. |
| group_shape | [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape) | Üst grup şekli. |
| shape_indexes | **List[int]** | Hizalanacak şekillerin indeksleri. |

### Ayrıca Bakınız
* sınıf [`IBaseSlide`](/slides/python-net/tr/aspose.slides/ibaseslide)
* sınıf [`IGroupShape`](/slides/python-net/tr/aspose.slides/igroupshape)
* enum [`ShapesAlignmentType`](/slides/python-net/tr/aspose.slides/shapesalignmenttype)
* sınıf [`SlideUtil`](/slides/python-net/tr/aspose.slides.util/slideutil)
* modül [`aspose.slides.util`](/slides/python-net/tr/aspose.slides.util)
* kütüphane [`Aspose.Slides`](/slides/python-net)