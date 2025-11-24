---
title: GetImage()
second_title: Aspose.Slides for C++ API Reference
description: "Returns shape thumbnail. ShapeThumbnailBounds::Shape shape thumbnail bounds type is used by default."
type: docs
weight: 651
url: /aspose.slides/shape/getimage/
---
## Shape::GetImage() method


Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) shape thumbnail bounds type is used by default.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```


### Return Value

[Shape](../) thumbnail.

## Shape::GetImage(ShapeThumbnailBounds, float, float) method


Returns shape thumbnail.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) thumbnail bounds type. |
| scaleX | **float** | X scale |
| scaleY | **float** | Y scale |

### Return Value

[Shape](../) thumbnail or null in case when [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) is used and a shape doesn't have visible elements.

## See Also

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)