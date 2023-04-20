---
title: SetSize()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the type of slide size and scales content using scale type. Assigning any value except SlideSizeType::Custom will change ISlideSize::get_Size accordingly, but will keep ISlideSize::get_Orientation intact."
type: docs
weight: 53
url: /cpp/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) method


Sets the type of slide size and scales content using scale type. Assigning any value except [SlideSizeType::Custom](../../slidesizetype/) will change [ISlideSize::get_Size](../get_size/) accordingly, but will keep [ISlideSize::get_Orientation](../get_orientation/) intact.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | [Slide](../../slide/) size type. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Scale type of slide content. |

## ISlideSize::SetSize(float, float, SlideSizeScaleType) method


Sets the size in points and scales content using scale type. Assigning any value will reset [ISlideSize::get_Type](../get_type/) value to [SlideSizeType::Custom](../../slidesizetype/) and set [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | **float** | Width. |
| height | **float** | Height. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Scale type of slide content. |

## See Also

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)