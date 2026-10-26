---
title: SlideImageFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: فرمت ذخیره‌سازی تصویر اسلاید برای ارائه در خروجی HTML را تعیین می‌کند.
type: docs
url: /fa/com.aspose.slides/slideimageformat/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

فرمت ذخیره‌سازی تصویر اسلاید برای ارائه به خروجی HTML را تعیین می‌کند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | اسلایدها باید به فرمت SVG تبدیل شوند. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | اسلایدها باید به تصویر رستر تبدیل شوند. |
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
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | گزینه‌های خروجی SVG. |

**برگشت:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - شیء [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

اسلایدها باید به تصویر رستر تبدیل شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scale | float | عاملی که برای مقیاس‌بندی تصویر خروجی به کار می‌رود. |
| imageFormat | int | فرمت تصویر حاصل (مثلاً PNG، JPEG). |

**برگشت:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -