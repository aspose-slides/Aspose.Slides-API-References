---
title: Clone()
second_title: مرجع API Aspose.Slides برای C++
description: یک نسخه از شیء فعلی ایجاد می‌کند.
type: docs
weight: 183
url: /fa/system.drawing/bitmap/clone/
---
## Bitmap::Clone() متد

یک نسخه از شیء فعلی را ایجاد می‌کند.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### مقدار بازگشتی

یک نسخه از شیء فعلی.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) متد

یک شیء [Bitmap](../) ایجاد می‌کند که نمایانگر یک نسخه از ناحیه‌ای از تصویر بیت‌مپ که توسط شیء فعلی نمایانده شده است.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | مستطیلی که ناحیه را برای کپی مشخص می‌کند |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | قالب پیکسل برای [Bitmap](../) جدید |

### مقدار بازگشتی

شیء [Bitmap](../) ایجاد‌شده

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) متد

یک شیء [Bitmap](../) ایجاد می‌کند که نمایانگر یک نسخه از ناحیه‌ای از تصویر بیت‌مپ که توسط شیء فعلی نمایانده شده است.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | مستطیلی که ناحیه را برای کپی مشخص می‌کند |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | قالب پیکسل برای [Bitmap](../) جدید |

### مقدار بازگشتی

شیء [Bitmap](../) ایجاد‌شده

## موارد مرتبط

* enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Image](../../image/)
* کلاس [Bitmap](../)
* کلاس [Rectangle](../../rectangle/)
* کلاس [RectangleF](../../rectanglef/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)