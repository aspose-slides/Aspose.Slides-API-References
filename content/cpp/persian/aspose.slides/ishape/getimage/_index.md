---
title: GetImage()
second_title: مرجع API Aspose.Slides برای C++
description: "یک تصویر کوچک از شکل را برمی‌گرداند. نوع bounds تصویر کوچک ShapeThumbnailBounds::Shape به طور پیش‌فرض استفاده می‌شود."
type: docs
weight: 547
url: /fa/aspose.slides/ishape/getimage/
---
## IShape::GetImage() متد

یک تصویر کوچک از شکل را برمی‌گرداند. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) نوع bounds تصویر کوچک شکل به طور پیش‌فرض استفاده می‌شود.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### مقدار برگشتی

[Shape](../../shape/) تصویر کوچک.

## IShape::GetImage(ShapeThumbnailBounds, float, float) متد

یک تصویر کوچک از شکل را برمی‌گرداند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) نوع bounds تصویر کوچک. |
| scaleX | **float** | مقیاس X |
| scaleY | **float** | مقیاس Y |

### مقدار برگشتی

[Shape](../../shape/) تصویر کوچک یا null در صورتی که [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) استفاده شود و یک شکل عناصر قابل مشاهده نداشته باشد.

## موارد مرتبط

* enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IImage](../../iimage/)
* کلاس [IShape](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)