---
title: EmbedAllFontsHtmlController
second_title: مرجع API Aspose.Slides برای جاوا
description: کلاس کنترل‌کننده قالب‌بندی که برای تعبیه تمام قلم‌های ارائه در فرمت WOFF استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/embedallfontshtmlcontroller/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

کلاس کنترل‌کننده قالب‌بندی که برای تعبیه تمام قلم‌های ارائه در قالب WOFF استفاده می‌شود.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Creates new instance |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Creates new instance |
## متدها

| متد | توضیح |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document header. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document footer. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide header. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide footer. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Write all fonts contained in [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Writes data as base64 into HTML document itself |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

یک نمونه جدید ایجاد می‌کند

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

یک نمونه جدید ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | قلم‌هایی که باید از تعبیه حذف شوند |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

برای نوشتن سرصفحه سند html فراخوانی می‌شود. یک بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه‌ای که در حال حاضر رندر می‌شود. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

برای نوشتن پابرگ سند html فراخوانی می‌شود. یک بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه‌ای که در حال حاضر رندر می‌شود. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

برای نوشتن سرصفحه اسلاید html فراخوانی می‌شود. یک بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که در حال حاضر رندر می‌شود. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

برای نوشتن پابرگ اسلاید html فراخوانی می‌شود. یک بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که در حال حاضر رندر می‌شود. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

قبل از رندر شکل فراخوانی می‌شود. یک بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، قطعه html افزوده شده درج می‌شود و تصویر جدیدی بالای قبلی شروع خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که در حال رندر شدن است. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

قبل از رندر شکل فراخوانی می‌شود. یک بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، قطعه html افزوده شده درج می‌شود و تصویر جدیدی بالای قبلی شروع خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که آخرین بار رندر می‌شود. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

تمام قلم‌های موجود در [Presentation](../../com.aspose.slides/presentation) را می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شیء خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه‌ای که در حال حاضر رندر می‌شود. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

داده‌ها را به صورت base64 در داخل سند HTML می‌نویسد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | تولیدکننده HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | قلم برای سریال‌سازی |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | قلم جایگزین (اگر تعویض قلم رخ داده باشد)، در غیر این صورت null |
| fontStyle | java.lang.String | استایل قلم |
| fontWeight | java.lang.String | وزن قلم |
| fontData | byte[] | داده‌های قلم |