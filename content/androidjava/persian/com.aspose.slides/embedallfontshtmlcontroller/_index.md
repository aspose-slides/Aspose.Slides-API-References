---
title: EmbedAllFontsHtmlController
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: کلاس کنترل‌کننده قالب‌بندی برای استفاده به منظور جاسازی تمام فونت‌های ارائه در قالب WOFF.
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

کلاس کنترل‌کننده قالب‌بندی برای استفاده به‌منظور جاسازی تمام فونت‌های ارائه در قالب WOFF.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | یک نمونه جدید ایجاد می‌کند |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | یک نمونه جدید ایجاد می‌کند |

## متدها

| متد | توضیح |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | برای نوشتن سرصفحه سند html فراخوانی می‌شود. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | برای نوشتن پاورق سند html فراخوانی می‌شود. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | برای نوشتن سرصفحه اسلاید html فراخوانی می‌شود. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | برای نوشتن پاورق اسلاید html فراخوانی می‌شود. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | قبل از رندر شدن شکل فراخوانی می‌شود. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | قبل از رندر شدن شکل فراخوانی می‌شود. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | تمام فونت‌های موجود در [Presentation](../../com.aspose.slides/presentation) را می‌نویسد. |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | داده‌ها را به صورت base64 در خود سند HTML می‌نویسد. |

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
| fontNameExcludeList | java.lang.String[] | فونت‌هایی که باید از جاسازی حذف شوند |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

برای نوشتن سرصفحه سند html فراخوانی می‌شود. یک بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | نمایشی که در حال حاضر رندر می‌شود. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

برای نوشتن پاورق سند html فراخوانی می‌شود. یک بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | نمایشی که در حال حاضر رندر می‌شود. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

برای نوشتن سرصفحه اسلاید html فراخوانی می‌شود. یک بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که در حال حاضر رندر می‌شود. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

برای نوشتن پاورق اسلاید html فراخوانی می‌شود. یک بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| slide | [ISlide](../../com.aspose.slides/islide) | اسلایدی که در حال حاضر رندر می‌شود. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

قبل از رندر شدن شکل فراخوانی می‌شود. یک بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، قطعه HTML افزوده می‌شود و تصویر جدیدی روی تصویر قبلی آغاز می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که قرار است رندر شود. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

قبل از رندر شدن شکل فراخوانی می‌شود. یک بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، قطعه HTML افزوده می‌شود و تصویر جدیدی روی تصویر قبلی آغاز می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که آخرین بار رندر می‌شود. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

تمام فونت‌های موجود در [Presentation](../../com.aspose.slides/presentation) را می‌نویسد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | شی خروجی. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | نمایشی که در حال حاضر رندر می‌شود. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

داده‌ها را به صورت base64 در خود سند HTML می‌نویسد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | مولد HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | فونتی که باید سریال‌سازی شود |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | فونت جایگزین (در صورت وقوع جایگزینی فونت)، در غیر این صورت null |
| fontStyle | java.lang.String | سبک فونت |
| fontWeight | java.lang.String | وزن فونت |
| fontData | byte[] | داده‌های فونت |