---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: تولید یک فایل html را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

تولید یک فایل html را کنترل می‌کند.
## متدها

| Method | Description |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | برای نوشتن هدر سند html فراخوانی می‌شود. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | برای نوشتن فوتر سند html فراخوانی می‌شود. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | برای نوشتن هدر اسلاید html فراخوانی می‌شود. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | برای نوشتن فوتر اسلاید html فراخوانی می‌شود. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | قبل از رندر شدن shape فراخوانی می‌شود. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | قبل از رندر شدن shape فراخوانی می‌شود. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

برای نوشتن هدر سند html فراخوانی می‌شود. یک بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation که در حال حاضر رندر می‌شود. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

برای نوشتن فوتر سند html فراخوانی می‌شود. یک بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentation که در حال حاضر رندر می‌شود. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

برای نوشتن هدر اسلاید html فراخوانی می‌شود. یک بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide که در حال حاضر رندر می‌شود. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

برای نوشتن فوتر اسلاید html فراخوانی می‌شود. یک بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide که در حال حاضر رندر می‌شود. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

قبل از رندر شدن shape فراخوانی می‌شود. یک بار برای هر shape فراخوانی می‌شود. اگر این تابع چیزی را به generator بنویسد، تولید تصویر slide فعلی تمام خواهد شد، بخش html اضافه شده درج می‌شود و تصویر جدید بر بالای قبلی آغاز می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape که در حال رندر شدن است. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

قبل از رندر شدن shape فراخوانی می‌شود. یک بار برای هر shape فراخوانی می‌شود. اگر این تابع چیزی را به generator بنویسد، تولید تصویر slide فعلی تمام خواهد شد، بخش html اضافه شده درج می‌شود و تصویر جدید بر بالای قبلی آغاز می‌شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape که آخرین بار رندر شده است. |