---
title: align_shapes method
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
更改幻灯片上所有形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh/aspose.slides/shapesalignmenttype) | 确定将应用哪种对齐方式。 |
| align_to_slide | **bool** | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| slide | [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide) | 父幻灯片。 |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
更改组形状内所有形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh/aspose.slides/shapesalignmenttype) | 确定将应用哪种对齐方式。 |
| align_to_slide | **bool** | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| group_shape | [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape) | 父组形状。 |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
更改幻灯片上所选形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh/aspose.slides/shapesalignmenttype) | 确定将应用哪种对齐方式。 |
| align_to_slide | **bool** | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| slide | [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide) | 父幻灯片。 |
| shape_indexes | **List[int]** | 要对齐的形状索引。 |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
更改组形状内所选形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh/aspose.slides/shapesalignmenttype) | 确定将应用哪种对齐方式。 |
| align_to_slide | **bool** | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| group_shape | [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape) | 父组形状。 |
| shape_indexes | **List[int]** | 要对齐的形状索引。 |

### 另请参见
* 类 [`IBaseSlide`](/slides/python-net/zh/aspose.slides/ibaseslide)
* 类 [`IGroupShape`](/slides/python-net/zh/aspose.slides/igroupshape)
* 枚举 [`ShapesAlignmentType`](/slides/python-net/zh/aspose.slides/shapesalignmenttype)
* 类 [`SlideUtil`](/slides/python-net/zh/aspose.slides.util/slideutil)
* 模块 [`aspose.slides.util`](/slides/python-net/zh/aspose.slides.util)
* 库 [`Aspose.Slides`](/slides/python-net)