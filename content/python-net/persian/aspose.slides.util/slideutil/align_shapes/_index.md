---
title: align_shapes method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.util/slideutil/align_shapes/
weight: 10
---
## align_shapes(alignment_type, align_to_slide, slide) {#shapesalignmenttype-bool-ibaseslide}
موقعیت تمام اشکال روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر موقعیت می‌دهد.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fa/aspose.slides/shapesalignmenttype) | نوع تراز مورد استفاده را تعیین می‌کند. |
| align_to_slide | **bool** | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| slide | [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide) | اسلاید والد. |

## align_shapes(alignment_type, align_to_slide, group_shape) {#shapesalignmenttype-bool-igroupshape}
موقعیت تمام اشکال داخل گروه اشکال را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر موقعیت می‌دهد.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fa/aspose.slides/shapesalignmenttype) | نوع تراز مورد استفاده را تعیین می‌کند. |
| align_to_slide | **bool** | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| group_shape | [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape) | گروه اشکال والد. |

## align_shapes(alignment_type, align_to_slide, slide, shape_indexes) {#shapesalignmenttype-bool-ibaseslide-listint}
موقعیت اشکال انتخاب‌شده روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر موقعیت می‌دهد.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, slide, shape_indexes):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fa/aspose.slides/shapesalignmenttype) | نوع تراز مورد استفاده را تعیین می‌کند. |
| align_to_slide | **bool** | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| slide | [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide) | اسلاید والد. |
| shape_indexes | **List[int]** | شاخص‌های اشکالی که باید تراز شوند. |

## align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes) {#shapesalignmenttype-bool-igroupshape-listint}
موقعیت اشکال انتخاب‌شده داخل گروه اشکال را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر موقعیت می‌دهد.

```python
@staticmethod
def align_shapes(alignment_type, align_to_slide, group_shape, shape_indexes):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| alignment_type | [`ShapesAlignmentType`](/slides/python-net/fa/aspose.slides/shapesalignmenttype) | نوع تراز مورد استفاده را تعیین می‌کند. |
| align_to_slide | **bool** | اگر مقدار true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| group_shape | [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape) | گروه اشکال والد. |
| shape_indexes | **List[int]** | شاخص‌های اشکالی که باید تراز شوند. |

### مراجع مرتبط
* کلاس [`IBaseSlide`](/slides/python-net/fa/aspose.slides/ibaseslide)
* کلاس [`IGroupShape`](/slides/python-net/fa/aspose.slides/igroupshape)
* شمارش [`ShapesAlignmentType`](/slides/python-net/fa/aspose.slides/shapesalignmenttype)
* کلاس [`SlideUtil`](/slides/python-net/fa/aspose.slides.util/slideutil)
* ماژول [`aspose.slides.util`](/slides/python-net/fa/aspose.slides.util)
* کتابخانه [`Aspose.Slides`](/slides/python-net)