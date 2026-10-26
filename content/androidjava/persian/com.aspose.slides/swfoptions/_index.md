---
title: SwfOptions
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: گزینه‌هایی را ارائه می‌دهد که نحوه ذخیره‌سازی یک ارائه در قالب Swf را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/swfoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

گزینه‌هایی را ارائه می‌دهد که نحوه ذخیره‌سازی یک ارائه در قالب Swf را کنترل می‌کند.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // یک شی Presentation ایجاد کنید که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // ذخیره‌سازی ارائه و صفحات یادداشت‌ها
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | سازنده پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getCompressed()](#getCompressed--) | مشخص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا نه. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | مشخص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا نه. |
| [getViewerIncluded()](#getViewerIncluded--) | مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. |
| [getShowPageBorder()](#getShowPageBorder--) | مشخص می‌کند که آیا حاشیه اطراف صفحات نمایش داده شود یا نه. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | مشخص می‌کند که آیا حاشیه اطراف صفحات نمایش داده شود یا نه. |
| [getShowFullScreen()](#getShowFullScreen--) | نمایش/پنهان کردن دکمه تمام‌صفحه. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | نمایش/پنهان کردن دکمه تمام‌صفحه. |
| [getShowPageStepper()](#getShowPageStepper--) | نمایش/پنهان کردن صفحه‌گام. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | نمایش/پنهان کردن صفحه‌گام. |
| [getShowSearch()](#getShowSearch--) | نمایش/پنهان کردن بخش جستجو. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | نمایش/پنهان کردن بخش جستجو. |
| [getShowTopPane()](#getShowTopPane--) | نمایش/پنهان کردن تمام نوار بالایی. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | نمایش/پنهان کردن تمام نوار بالایی. |
| [getShowBottomPane()](#getShowBottomPane--) | نمایش/پنهان کردن نوار پایین. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | نمایش/پنهان کردن نوار پایین. |
| [getShowLeftPane()](#getShowLeftPane--) | نمایش/پنهان کردن نوار چپ. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | نمایش/پنهان کردن نوار چپ. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | شروع با نوار چپ باز. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | شروع با نوار چپ باز. |
| [getEnableContextMenu()](#getEnableContextMenu--) | فعال/غیرفعال کردن منوی زمینه. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | فعال/غیرفعال کردن منوی زمینه. |
| [getLogoImageBytes()](#getLogoImageBytes--) | تصویری که به‌عنوان لوگو در گوشه راست بالای نمایشگر ظاهر می‌شود. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | تصویری که به‌عنوان لوگو در گوشه راست بالای نمایشگر ظاهر می‌شود. |
| [getLogoLink()](#getLogoLink--) | آدرس کامل پیوند برای یک لوگو را دریافت یا تنظیم می‌کند. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | آدرس کامل پیوند برای یک لوگو را دریافت یا تنظیم می‌کند. |
| [getJpegQuality()](#getJpegQuality--) | کیفیت تصاویر JPEG را مشخص می‌کند. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | کیفیت تصاویر JPEG را مشخص می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند. |

### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

سازنده پیش‌فرض.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

مشخص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا نه. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

مشخص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا نه. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

مشخص می‌کند که آیا حاشیه اطراف صفحات نمایش داده شود یا نه. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

مشخص می‌کند که آیا حاشیه اطراف صفحات نمایش داده شود یا نه. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

نمایش/پنهان کردن دکمه تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

نمایش/پنهان کردن دکمه تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

نمایش/پنهان کردن صفحه‌گام. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

نمایش/پنهان کردن صفحه‌گام. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

نمایش/پنهان کردن بخش جستجو. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

نمایش/پنهان کردن بخش جستجو. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

نمایش/پنهان کردن تمام نوار بالایی. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

نمایش/پنهان کردن تمام نوار بالایی. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

نمایش/پنهان کردن نوار پایین. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

نمایش/پنهان کردن نوار پایین. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

نمایش/پنهان کردن نوار چپ. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

نمایش/پنهان کردن نوار چپ. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

شروع با نوار چپ باز. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

شروع با نوار چپ باز. می‌تواند در flashvars بازنویسی شود. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

فعال/غیرفعال کردن منوی زمینه. مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

فعال/غیرفعال کردن منوی زمینه. مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

تصویری که به‌عنوان لوگو در گوشه راست بالای نمایشگر ظاهر می‌شود. تصویر باید PNG با ابعاد 32x64 پیکسل باشد، در غیر این صورت لوگو ممکن است به‌درستی نمایش داده نشود.

**بازگشت:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

تصویری که به‌عنوان لوگو در گوشه راست بالای نمایشگر ظاهر می‌شود. تصویر باید PNG با ابعاد 32x64 پیکسل باشد، در غیر این صورت لوگو ممکن است به‌درستی نمایش داده نشود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

آدرس کامل پیوند برای یک لوگو را دریافت یا تنظیم می‌کند. تنها در صورتی مؤثر است که (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) مشخص شود.

**بازگشت:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

آدرس کامل پیوند برای یک لوگو را دریافت یا تنظیم می‌کند. تنها در صورتی مؤثر است که (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) مشخص شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

کیفیت تصاویر JPEG را مشخص می‌کند. مقدار پیش‌فرض 95 است.

**بازگشت:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

کیفیت تصاویر JPEG را مشخص می‌کند. مقدار پیش‌فرض 95 است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند. این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) پشتیبانی نمی‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند. این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) پشتیبانی نمی‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |