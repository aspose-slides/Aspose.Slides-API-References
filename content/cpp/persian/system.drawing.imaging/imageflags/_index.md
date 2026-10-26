---
title: ImageFlags
second_title: مرجع API Aspose.Slides برای C++
description: ویژگی‌های داده‌های پیکسلی که توسط یک شیء Image نمایان می‌شود را توصیف می‌کند.
type: docs
weight: 274
url: /fa/system.drawing.imaging/imageflags/
---
## ImageFlags enum

ویژگی‌های داده‌های پیکسلی که توسط شیء [Image](../../system.drawing/image/) نمایان شده‌اند را توصیف می‌کند.

```cpp
enum class ImageFlags
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | قابل مقیاس‌سازی. |
| HasAlpha | 2 | اطلاعات آلفا را شامل می‌شود. |
| HasTranslucent | 4 | مقادیر آلفا بزرگتر از 0 و کمتر از 255 وجود دارد. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | داده‌های پیکسل در فضای رنگی RGB نمایان شده‌اند. |
| ColorSpaceCmyk | 32 | داده‌های پیکسل در فضای رنگی CMYK نمایان شده‌اند. |
| ColorSpaceGray | 64 | داده‌های پیکسل در مقیاس خاکستری هستند. |
| ColorSpaceYcbcr | 128 | داده‌های پیکسل در فضای رنگی YCBCR نمایان شده‌اند. |
| ColorSpaceYcck | 256 | داده‌های پیکسل در فضای رنگی YCCK نمایان شده‌اند. |
| HasRealDpi | 4096 | اطلاعات DPI در تصویر ذخیره شده است. |
| HasRealPixelSize | 8192 | اندازه یک پیکسل در تصویر ذخیره شده است. |
| ReadOnly | 65536 | داده‌های پیکسل فقط‌خواندنی هستند. |
| Caching | 131072 | قابل ذخیره‌سازی برای دسترسی سریع‌تر است. |

## مراجع

* فضای‌نام [System::Drawing::Imaging](../)
* کتابخانه [Aspose.Slides](../../)