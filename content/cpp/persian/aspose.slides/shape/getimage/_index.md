---
title: GetImage()
second_title: Aspose.Slides برای مرجع API C++
description: "تصویر بندانگشتی شکل را برمی‌گرداند. نوع محدوده تصویر بندانگشتی ShapeThumbnailBounds::Shape به طور پیش‌فرض استفاده می‌شود."
type: docs
weight: 651
url: /fa/aspose.slides/shape/getimage/
---
## Shape::GetImage() method

تصویر بندانگشتی شکل را برمی‌گرداند. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) نوع محدوده تصویر بندانگشتی شکل به طور پیش‌فرض استفاده می‌شود.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### مقدار بازگشتی

[Shape](../) تصویر بندانگشتی.

## Shape::GetImage(ShapeThumbnailBounds, float, float) متد

تصویر بندانگشتی شکل را برمی‌گرداند.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) نوع محدوده تصویر بندانگشتی |
| scaleX | **float** | مقیاس X |
| scaleY | **float** | مقیاس Y |

### مقدار بازگشتی

[Shape](../) تصویر بندانگشتی یا null در صورتی که [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) استفاده شود و شکل عناصر قابل مشاهده‌ای نداشته باشد.

## مراجع

* enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IImage](../../iimage/)
* کلاس [Shape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)