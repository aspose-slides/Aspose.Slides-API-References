---
title: SetSize()
second_title: Aspose.Slides for C++ API Reference
description: Sets the slide size by type and scales existing content.
type: docs
weight: 53
url: /aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) method


Sets the slide size by type and scales existing content.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## Remarks


Assigning any value other than [SlideSizeType::Custom](../../slidesizetype/) adjusts the [SlideSize::get_Size](../get_size/) based on the selected type, while preserving [SlideSize::get_Orientation](../get_orientation/). 

## SlideSize::SetSize(float, float, SlideSizeScaleType) method


Sets the slide dimensions explicitly and scales existing content.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## Remarks


This resets the [SlideSize::get_Type](../get_type/) property to [SlideSizeType::Custom](../../slidesizetype/) and sets the [Orientation](../../orientation/). 

## See Also

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Class [SlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)