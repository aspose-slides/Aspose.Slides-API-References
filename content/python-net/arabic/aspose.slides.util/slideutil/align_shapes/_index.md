---
title: align_shapes method
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
يغيّر موضع جميع الأشكال على الشريحة. ينسق الأشكال إلى الهوامش أو حافة الشريحة أو ينسقها بالنسبة لبعضها البعض.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ar/aspose.slides/shapesalignmenttype) | يحدد نوع المحاذاة الذي سيُطبق. |
| align_to_slide | **bool** | إذا كان صحيحًا، سيتم محاذاة الأشكال بالنسبة لحواف الشريحة. |
| slide | [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide) | الشريحة الأصلية. |


## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
يغيّر موضع جميع الأشكال داخل مجموعة الشكل. ينسق الأشكال إلى الهوامش أو حافة الشريحة أو ينسقها بالنسبة لبعضها البعض.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ar/aspose.slides/shapesalignmenttype) | يحدد نوع المحاذاة الذي سيُطبق. |
| align_to_slide | **bool** | إذا كان صحيحًا، سيتم محاذاة الأشكال بالنسبة لحواف الشريحة. |
| group_shape | [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape) | شكل المجموعة الأصلية. |


## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
يغيّر موضع الأشكال المختارة على الشريحة. ينسق الأشكال إلى الهوامش أو حافة الشريحة أو ينسقها بالنسبة لبعضها البعض.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ar/aspose.slides/shapesalignmenttype) | يحدد نوع المحاذاة الذي سيُطبق. |
| align_to_slide | **bool** | إذا كان صحيحًا، سيتم محاذاة الأشكال بالنسبة لحواف الشريحة. |
| slide | [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide) | الشريحة الأصلية. |
| shape_indexes | **List[int]** | فهرس الأشكال التي سيتم محاذاتها. |


## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
يغيّر موضع الأشكال المختارة داخل مجموعة الشكل. ينسق الأشكال إلى الهوامش أو حافة الشريحة أو ينسقها بالنسبة لبعضها البعض.


```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/ar/aspose.slides/shapesalignmenttype) | يحدد نوع المحاذاة الذي سيُطبق. |
| align_to_slide | **bool** | إذا كان صحيحًا، سيتم محاذاة الأشكال بالنسبة لحواف الشريحة. |
| group_shape | [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape) | شكل المجموعة الأصلية. |
| shape_indexes | **List[int]** | فهرس الأشكال التي سيتم محاذاتها. |



### انظر أيضًا
* فئة [`IBaseSlide`](/slides/python-net/ar/aspose.slides/ibaseslide)
* فئة [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape)
* تعداد [`ShapesAlignmentType`](/slides/python-net/ar/aspose.slides/shapesalignmenttype)
* فئة [`SlideUtil`](/slides/python-net/ar/aspose.slides.util/slideutil)
* وحدة [`aspose.slides.util`](/slides/python-net/ar/aspose.slides.util)
* مكتبة [`Aspose.Slides`](/slides/python-net)