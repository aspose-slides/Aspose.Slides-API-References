---
title: SetSize()
second_title: Aspose.Slides for C++ API Reference
description: Sets the type of slide size and scales content using scale type.
type: docs
weight: 53
url: /aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) method


Sets the type of slide size and scales content using scale type.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | [Slide](../../slide/) size type. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Scale type of slide content. |
## Remarks


Assigning any value except [SlideSizeType::Custom](../../slidesizetype/) will change [SlideSize::get_Size](../get_size/) accordingly, but will keep [SlideSize::get_Orientation](../get_orientation/) intact.

## SlideSize::SetSize(float, float, SlideSizeScaleType) method


Sets the size in points and scales content using scale type.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | **float** | Width. |
| height | **float** | Height. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Scale type of slide content. |
## Remarks


Assigning any value will reset [Type](../get_type/) property to [SlideSizeType::Custom](../../slidesizetype/) and set [SlideSize::get_Orientation()](../get_orientation/).

## See Also

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [SlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)