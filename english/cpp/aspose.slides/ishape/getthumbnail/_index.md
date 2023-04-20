---
title: GetThumbnail()
second_title: Aspose.Slides for C++ API Reference
description: "Returns shape thumbnail. ShapeThumbnailBounds::Shape shape thumbnail bounds type is used by default."
type: docs
weight: 521
url: /cpp/aspose.slides/ishape/getthumbnail/
---
## IShape::GetThumbnail() method


Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type is used by default.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::IShape::GetThumbnail()=0
```


### Return Value

[Shape](../../shape/) thumbnail.

## IShape::GetThumbnail(ShapeThumbnailBounds, float, float) method


Returns shape thumbnail.

```cpp
virtual System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::IShape::GetThumbnail(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) thumbnail bounds type. |
| scaleX | **float** | X scale |
| scaleY | **float** | Y scale |

### Return Value

[Shape](../../shape/) thumbnail or null in case when [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) is used and a shape doesn't have visible elements.

## See Also

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)