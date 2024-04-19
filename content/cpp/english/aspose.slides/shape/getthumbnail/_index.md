---
title: GetThumbnail()
second_title: Aspose.Slides for C++ API Reference
description: "Returns shape thumbnail. ShapeThumbnailBounds::Shape shape thumbnail bounds type is used by default."
type: docs
weight: 651
url: /aspose.slides/shape/getthumbnail/
---
## Shape::GetThumbnail() method


Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type is used by default.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Shape::GetThumbnail() override
```


### Return Value

[Shape](../) thumbnail.

Deprecated
:   Use GetImage method instead. The method will be removed after release of version 24.7.

## Shape::GetThumbnail(ShapeThumbnailBounds, float, float) method


Returns shape thumbnail.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Shape::GetThumbnail(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) thumbnail bounds type. |
| scaleX | **float** | X scale |
| scaleY | **float** | Y scale |

### Return Value

[Shape](../) thumbnail or null in case when [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) is used and a shape doesn't have visible elements.

Deprecated
:   Use [GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)](../getimage/) method instead. The method will be removed after release of version 24.7.

## See Also

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)