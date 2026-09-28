---
title: GetTile()
second_title: Aspose.Slides برای C++ مرجع API
description: یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) متد

یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | [System::Drawing::Color](../../../system.drawing/color/) پس‌زمینه برای الگو. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | [System::Drawing::Color](../../../system.drawing/color/) پیش‌زمینه برای الگو. |

### مقدار بازگشت

کاشی [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) متد

یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | [System::Drawing::Color](../../../system.drawing/color/) پیش‌فرض، تعریف‌شده در شیء StyleEx مربوط به ShapeEx. رنگ‌های پرکننده می‌توانند به این مقدار وابسته باشند. |

### مقدار بازگشت

کاشی [IImage](../../iimage/).

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IImage](../../iimage/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [IPatternFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)