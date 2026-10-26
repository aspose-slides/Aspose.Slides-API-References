---
title: GetImage()
second_title: Aspose.Slides لمرجع API للغة C++
description: "يرجع صورة مصغرة للشكل. يُستخدم نوع حدود الصورة المصغرة ShapeThumbnailBounds::Shape بشكل افتراضي."
type: docs
weight: 547
url: /ar/aspose.slides/ishape/getimage/
---
## IShape::GetImage() طريقة

يرجع صورة مصغرة للشكل. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) نوع حدود الصورة المصغرة للشكل يُستخدم بشكل افتراضي.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### قيمة الإرجاع

[Shape](../../shape/) صورة مصغرة.

## IShape::GetImage(ShapeThumbnailBounds, float, float) طريقة

يرجع صورة مصغرة للشكل.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) نوع حدود الصورة المصغرة. |
| scaleX | **float** | مقياس X |
| scaleY | **float** | مقياس Y |

### قيمة الإرجاع

[Shape](../../shape/) صورة مصغرة أو null في حالة استخدام [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) وعند عدم وجود عناصر مرئية للشكل.

## انظر أيضًا

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)