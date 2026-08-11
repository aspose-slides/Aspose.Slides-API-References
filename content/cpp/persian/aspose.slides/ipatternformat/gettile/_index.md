---
title: GetTile()
second_title: مرجع API Aspose.Slides برای C++
description: یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.
type: docs
weight: 53
url: /fa/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) روش

یک تصویر کاشی برای پر کردن الگو با رنگ‌های مشخص ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | پس‌زمینه [System::Drawing::Color](../../../system.drawing/color/) برای الگو. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | پیش‌زمینه [System::Drawing::Color](../../../system.drawing/color/) برای الگو. |

### مقدار بازگشت

کاشه [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) روش

یک تصویر کاشی برای پر کردن الگو ایجاد می‌کند.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | مقدار پیش‌فرض [System::Drawing::Color](../../../system.drawing/color/) که در شیء StyleEx از ShapeEx تعریف شده است. رنگ‌های پرکننده می‌توانند به این مقدار وابسته باشند. |

### مقدار بازگشت

کاشه [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IImage](../../iimage/)
* کلاس [Color](../../../system.drawing/color/)
* کلاس [IPatternFormat](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)