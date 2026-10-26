---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: یک فایل html را تولید می‌کند.
type: docs
url: /fa/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

یک فایل html را تولید می‌کند.
## متدها

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | برای نوشتن هدر سند html فراخوانی می‌شود. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | برای نوشتن فوتر سند html فراخوانی می‌شود. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | برای نوشتن هدر اسلاید html فراخوانی می‌شود. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | برای نوشتن فوتر اسلاید html فراخوانی می‌شود. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | قبل از رندر شدن شکل فراخوانی می‌شود. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | قبل از رندر شدن شکل فراخوانی می‌شود. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن هدر سند html فراخوانی می‌شود. برای هر تبدیل ارائه یک بار فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه‌ای که در حال حاضر رندر می‌شود. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن فوتر سند html فراخوانی می‌شود. برای هر تبدیل ارائه یک بار فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه‌ای که در حال حاضر رندر می‌شود. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن هدر اسلاید html فراخوانی می‌شود. برای هر اسلاید یک بار فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که در حال حاضر رندر می‌شود. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن فوتر اسلاید html فراخوانی می‌شود. برای هر اسلاید یک بار فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که در حال حاضر رندر می‌شود. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


قبل از رندر شدن شکل فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید فعلی تمام می‌شود، جزء html اضافه شده درج می‌گردد و تصویر جدیدی بر فراز قبلی شروع می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که در حال رندر شدن است. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


قبل از رندر شدن شکل فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید فعلی تمام می‌شود، جزء html اضافه شده درج می‌گردد و تصویر جدیدی بر فراز قبلی شروع می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که آخرین بار رندر شده است. |