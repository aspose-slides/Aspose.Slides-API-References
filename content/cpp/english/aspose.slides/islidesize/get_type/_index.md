---
title: get_Type()
second_title: Aspose.Slides for C++ API Reference
description: "Gets the slide size type. Assigning any value except SlideSizeType::Custom adjusts the ISlideSize::get_Size according to the predefined dimensions, while retaining the current ISlideSize::get_Orientation."
type: docs
weight: 14
url: /aspose.slides/islidesize/get_type/
---
## ISlideSize::get_Type() method


Gets the slide size type. Assigning any value except [SlideSizeType::Custom](../../slidesizetype/) adjusts the [ISlideSize::get_Size](../get_size/) according to the predefined dimensions, while retaining the current [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual SlideSizeType Aspose::Slides::ISlideSize::get_Type()=0
```

## Remarks


Assigning any value other than [SlideSizeType::Custom](../../slidesizetype/) adjusts the [System::Drawing::Size](../../../system.drawing/size/) according to the predefined dimensions, while retaining the current [Orientation](../../orientation/). 
## See Also

* Enum [SlideSizeType](../../slidesizetype/)
* Class [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)