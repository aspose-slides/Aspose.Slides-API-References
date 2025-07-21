---
title: SetSize()
second_title: Aspose.Slides for C++ API Reference
description: "Sets the slide size by type and scales existing content. Assigning any value other than SlideSizeType::Custom adjusts the ISlideSize::get_Size based on the selected type, while preserving ISlideSize::get_Orientation."
type: docs
weight: 53
url: /aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) method


Sets the slide size by type and scales existing content. Assigning any value other than [SlideSizeType::Custom](../../slidesizetype/) adjusts the [ISlideSize::get_Size](../get_size/) based on the selected type, while preserving [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## Remarks


Assigning any value other than [SlideSizeType::Custom](../../slidesizetype/) adjusts the [System::Drawing::Size](../../../system.drawing/size/) based on the selected type, while preserving [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) method


Sets the slide dimensions explicitly and scales existing content. This resets the [ISlideSize::get_Type](../get_type/) value to [SlideSizeType::Custom](../../slidesizetype/) and sets the [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## Remarks


This resets the [ISlideSize::get_Type](../get_type/) property to [SlideSizeType::Custom](../../slidesizetype/) and sets the [Orientation](../../orientation/). 

## See Also

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)