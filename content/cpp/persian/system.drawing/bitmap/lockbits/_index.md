---
title: LockBits()
second_title: مرجع API برای Aspose.Slides در C++
description: یک Bitmap را در حافظهٔ سیستم قفل می‌کند.
type: docs
weight: 118
url: /fa/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method

یک [Bitmap](../) را در حافظهٔ سیستم قفل می‌کند.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطیلی که ناحیهٔ تصویر برای قفل کردن را مشخص می‌کند |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | سطح دسترسی به bitmap را تعیین می‌کند |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | قالب دادهٔ این bitmap |

### Return Value

یک اشاره‌گر اشتراکی به شیء BitmapData که شامل اطلاعات درباره عملیات قفل‌گذاری انجام‌شده است

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method

یک [Bitmap](../) را در حافظهٔ سیستم قفل می‌کند.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | مستطیلی که ناحیهٔ تصویر برای قفل کردن را مشخص می‌کند |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | سطح دسترسی به bitmap را تعیین می‌کند |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | قالب دادهٔ این bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | شامل اطلاعات درباره عملیات قفل‌گذاری است |

### Return Value

یک اشاره‌گر اشتراکی به شیء BitmapData که شامل اطلاعات درباره عملیات قفل‌گذاری انجام‌شده است

## See Also

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)