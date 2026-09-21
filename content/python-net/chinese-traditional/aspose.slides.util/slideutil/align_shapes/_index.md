---
title: align_shapes method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
變更投影片上所有圖形的位置。將圖形對齊至投影片的邊緣或邊框，或使它們相互對齊。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh-hant/aspose.slides/shapesalignmenttype) | 確定要套用哪種對齊類型。 |
| align_to_slide | **bool** | 如果為 true，圖形將相對於投影片邊緣對齊。 |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 父投影片。 |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
變更群組圖形內所有圖形的位置。將圖形對齊至投影片的邊緣或邊框，或使它們相互對齊。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh-hant/aspose.slides/shapesalignmenttype) | 確定要套用哪種對齊類型。 |
| align_to_slide | **bool** | 如果為 true，圖形將相對於投影片邊緣對齊。 |
| group_shape | [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape) | 父群組圖形。 |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
變更投影片上選取圖形的位置。將圖形對齊至投影片的邊緣或邊框，或使它們相互對齊。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh-hant/aspose.slides/shapesalignmenttype) | 確定要套用哪種對齊類型。 |
| align_to_slide | **bool** | 如果為 true，圖形將相對於投影片邊緣對齊。 |
| slide | [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide) | 父投影片。 |
| shape_indexes | **List[int]** | 要對齊的圖形索引。 |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
變更群組圖形內選取圖形的位置。將圖形對齊至投影片的邊緣或邊框，或使它們相互對齊。

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/zh-hant/aspose.slides/shapesalignmenttype) | 確定要套用哪種對齊類型。 |
| align_to_slide | **bool** | 如果為 true，圖形將相對於投影片邊緣對齊。 |
| group_shape | [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape) | 父群組圖形。 |
| shape_indexes | **List[int]** | 要對齊的圖形索引。 |

### 參見
* 類別 [`IBaseSlide`](/slides/python-net/zh-hant/aspose.slides/ibaseslide)
* 類別 [`IGroupShape`](/slides/python-net/zh-hant/aspose.slides/igroupshape)
* 列舉 [`ShapesAlignmentType`](/slides/python-net/zh-hant/aspose.slides/shapesalignmenttype)
* 類別 [`SlideUtil`](/slides/python-net/zh-hant/aspose.slides.util/slideutil)
* 模組 [`aspose.slides.util`](/slides/python-net/zh-hant/aspose.slides.util)
* 函式庫 [`Aspose.Slides`](/slides/python-net)