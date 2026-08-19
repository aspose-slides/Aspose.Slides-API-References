---
title: EmbeddedEotFontsHtmlController
second_title: مرجع API Aspose.Slides برای جاوا
description: کلاس کنترل‌کننده قالب‌بندی برای استفاده در جاسازی قلم‌ها در فرمت EOT
type: docs
url: /fa/com.aspose.slides/embeddedeotfontshtmlcontroller/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IEmbeddedEotFontsHtmlController](../../com.aspose.slides/iembeddedeotfontshtmlcontroller)
```
public class EmbeddedEotFontsHtmlController implements IEmbeddedEotFontsHtmlController
```

کلاس کنترل‌کننده قالب‌بندی برای استفاده در جاسازی قلم‌ها در قالب EOT

## Constructors

| سازنده | توضیح |
| --- | --- |
| [EmbeddedEotFontsHtmlController()](#EmbeddedEotFontsHtmlController--) | یک نمونه جدید ایجاد می‌کند. |
| [EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | یک نمونه جدید ایجاد می‌کند. |
## Methods

| متد | توضیح |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedEotFontsHtmlController() {#EmbeddedEotFontsHtmlController--}
```
public EmbeddedEotFontsHtmlController()
```


یک نمونه جدید ایجاد می‌کند.

### EmbeddedEotFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedEotFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedEotFontsHtmlController(IHtmlFormattingController controller)
```


یک نمونه جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | کنترل‌کننده قالب‌بندی HTML. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن هدر سند html فراخوانی می‌شود. یک‌بار برای هر تبدیل ارائه اجرا می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن فوتر سند html فراخوانی می‌شود. یک‌بار برای هر تبدیل ارائه اجرا می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن هدر اسلاید html فراخوانی می‌شود. یک‌بار برای هر اسلاید اجرا می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن فوتر اسلاید html فراخوانی می‌شود. یک‌بار برای هر اسلاید اجرا می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


قبل از رندر شکل فراخوانی می‌شود. یک‌بار برای هر شکل اجرا می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری خاتمه می‌یابد، تکه html اضافه می‌شود و تصویر جدید در بالای قبلی آغاز می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


قبل از رندر شکل فراخوانی می‌شود. یک‌بار برای هر شکل اجرا می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری خاتمه می‌یابد، تکه html اضافه می‌شود و تصویر جدید در بالای قبلی آغاز می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |