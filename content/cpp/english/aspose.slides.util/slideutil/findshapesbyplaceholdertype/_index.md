---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides for C++ API Reference
description: Searches for all shapes on the specified slide that match the given placeholder type.
type: docs
weight: 14
url: /aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) method


Searches for all shapes on the specified slide that match the given placeholder type.

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | The slide to search for shapes. |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | The type of placeholder to filter shapes by. |

### Return Value

An array of [IShape](../../../aspose.slides/ishape/) objects that match the specified placeholder type.

## See Also

* Enum [PlaceholderType](../../../aspose.slides/placeholdertype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)