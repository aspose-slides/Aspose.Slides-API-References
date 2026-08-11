---
title: GetImage()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: "يرجع صورة مصغرة للشكل. يتم استخدام نوع حدود الصورة المصغرة ShapeThumbnailBounds::Shape بشكل افتراضي."
type: docs
weight: 651
url: /ar/aspose.slides/shape/getimage/
---
## Shape::GetImage() طريقة

يرجع صورة مصغرة للشكل. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) يتم استخدام نوع حدود الصورة المصغرة للشكل بشكل افتراضي.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### قيمة الإرجاع

[Shape](../) صورة مصغرة.

## Shape::GetImage(ShapeThumbnailBounds, float, float) طريقة

يرجع صورة مصغرة للشكل.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) نوع حدود الصورة المصغرة. |
| scaleX | **float** | مقياس X |
| scaleY | **float** | مقياس Y |

### قيمة الإرجاع

[Shape](../) صورة مصغرة أو null في حالة استخدام [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) وعدم وجود عناصر مرئية للشكل.

## انظر أيضا

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../iimage/)
* فئة [Shape](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)