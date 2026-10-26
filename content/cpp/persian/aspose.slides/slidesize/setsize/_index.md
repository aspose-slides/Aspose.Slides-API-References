---
title: SetSize()
second_title: مرجع API Aspose.Slides برای C++
description: اندازه اسلاید را بر اساس نوع تنظیم می‌کند و محتویات موجود را مقیاس می‌گیرد.
type: docs
weight: 53
url: /fa/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) متد

Sets the slide size by type and scales existing content.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |

## توضیحات

Assigning any value other than [SlideSizeType::Custom](../../slidesizetype/) adjusts the [SlideSize::get_Size](../get_size/) based on the selected type, while preserving [SlideSize::get_Orientation](../get_orientation/).

## SlideSize::SetSize(float, float, SlideSizeScaleType) متد

Sets the slide dimensions explicitly and scales existing content.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |

## توضیحات

This resets the [SlideSize::get_Type](../get_type/) property to [SlideSizeType::Custom](../../slidesizetype/) and sets the [Orientation](../../orientation/).

## موارد مرتبط

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [SlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)