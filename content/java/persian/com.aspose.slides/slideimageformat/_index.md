---
title: SlideImageFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: قالبی را که تصویر اسلاید برای ارائه به خروجی HTML ذخیره می‌شود، تعیین می‌کند.
type: docs
url: /fa/com.aspose.slides/slideimageformat/
---
**ارث‌بری:**
java.lang.Object

**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

قالبی را که تصویر اسلاید برای ارائه به خروجی HTML ذخیره می‌شود، تعیین می‌کند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | اسلایدها باید به فرمت SVG تبدیل شوند. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | اسلایدها باید به تصویر شطرنجی (رستر) تبدیل شوند. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

اسلایدها باید به فرمت SVG تبدیل شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | گزینه‌ها برای خروجی SVG. |

**بازگشت:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - شیء [SlideImageFormat](../../com.aspose.slides/slideimageformat)
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

اسلایدها باید به تصویر شطرنجی (رستر) تبدیل شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scale | float | فاکتری که برای تغییر مقیاس تصویر خروجی استفاده می‌شود. |
| imageFormat | int | قالب تصویر حاصل (مثلاً PNG، JPEG). |

**بازگشت:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -