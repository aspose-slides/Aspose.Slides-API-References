---
title: ISwfOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب SWF را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/iswfoptions/
---
**همهٔ رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب SWF را کنترل می‌کند.

## متدها

| Method | Description |
| --- | --- |
| [getCompressed()](#getCompressed--) | مشخص می‌کند که آیا سند SWF تولید شده باید فشرده باشد یا نه. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | مشخص می‌کند که آیا سند SWF تولید شده باید فشرده باشد یا نه. |
| [getViewerIncluded()](#getViewerIncluded--) | مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. |
| [getShowPageBorder()](#getShowPageBorder--) | مشخص می‌کند که آیا حاشیه دور صفحات نشان داده شود یا خیر. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | مشخص می‌کند که آیا حاشیه دور صفحات نشان داده شود یا خیر. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. |
| [getShowFullScreen()](#getShowFullScreen--) | نمایش/مخفی‌سازی دکمه تمام‌صفحه. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | نمایش/مخفی‌سازی دکمه تمام‌صفحه. |
| [getShowPageStepper()](#getShowPageStepper--) | نمایش/مخفی‌سازی نوار قدم‌گیر صفحه. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | نمایش/مخفی‌سازی نوار قدم‌گیر صفحه. |
| [getShowSearch()](#getShowSearch--) | نمایش/مخفی‌سازی بخش جستجو. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | نمایش/مخفی‌سازی بخش جستجو. |
| [getShowTopPane()](#getShowTopPane--) | نمایش/مخفی‌سازی کل پنل بالایی. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | نمایش/مخفی‌سازی کل پنل بالایی. |
| [getShowBottomPane()](#getShowBottomPane--) | نمایش/مخفی‌سازی پنل پایینی. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | نمایش/مخفی‌سازی پنل پایینی. |
| [getShowLeftPane()](#getShowLeftPane--) | نمایش/مخفی‌سازی پنل سمت چپ. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | نمایش/مخفی‌سازی پنل سمت چپ. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | شروع با پنل سمت چپ باز. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | شروع با پنل سمت چپ باز. |
| [getEnableContextMenu()](#getEnableContextMenu--) | فعال/غیرفعال کردن منوی زمینه. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | فعال/غیرفعال کردن منوی زمینه. |
| [getLogoImageBytes()](#getLogoImageBytes--) | تصویری که به عنوان لوگو در گوشه بالای راست نمایشگر نشان داده خواهد شد. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | تصویری که به عنوان لوگو در گوشه بالای راست نمایشگر نشان داده خواهد شد. |
| [getLogoLink()](#getLogoLink--) | آدرس کامل پیوند هیپرمتن برای لوگو را دریافت یا تنظیم می‌کند. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | آدرس کامل پیوند هیپرمتن برای لوگو را دریافت یا تنظیم می‌کند. |
| [getJpegQuality()](#getJpegQuality--) | کیفیت تصاویر JPEG را مشخص می‌کند. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | کیفیت تصاویر JPEG را مشخص می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

مشخص می‌کند که آیا سند SWF تولید شده باید فشرده باشد یا نه. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

مشخص می‌کند که آیا سند SWF تولید شده باید فشرده باشد یا نه. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

مشخص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا نه. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

مشخص می‌کند که آیا حاشیه دور صفحات نشان داده شود یا خیر. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

مشخص می‌کند که آیا حاشیه دور صفحات نشان داده شود یا خیر. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. به‌طور پیش‌فرض false است.

**باز می‌گردد:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای پنهان را شامل شود یا نه. به‌طور پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

نمایش/مخفی‌سازی دکمه تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

نمایش/مخفی‌سازی دکمه تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

نمایش/مخفی‌سازی نوار قدم‌گیر صفحه. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

نمایش/مخفی‌سازی نوار قدم‌گیر صفحه. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

نمایش/مخفی‌سازی بخش جستجو. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

نمایش/مخفی‌سازی بخش جستجو. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

نمایش/مخفی‌سازی کل پنل بالایی. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

نمایش/مخفی‌سازی کل پنل بالایی. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

نمایش/مخفی‌سازی پنل پایینی. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

نمایش/مخفی‌سازی پنل پایینی. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

نمایش/مخفی‌سازی پنل سمت چپ. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

نمایش/مخفی‌سازی پنل سمت چپ. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

شروع با پنل سمت چپ باز. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض false است.

**باز می‌گردد:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

شروع با پنل سمت چپ باز. می‌تواند در flashvars بازنویسی شود. به‌طور پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

فعال/غیرفعال کردن منوی زمینه. به‌طور پیش‌فرض true است.

**باز می‌گردد:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

فعال/غیرفعال کردن منوی زمینه. به‌طور پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

تصویری که به عنوان لوگو در گوشه بالای راست نمایشگر نشان داده خواهد شد. تصویر باید PNG به اندازهٔ ۳۲×۶۴ پیکسل باشد، در غیر این صورت ممکن است لوگو به‌درستی نمایش داده نشود.

**باز می‌گردد:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

تصویری که به عنوان لوگو در گوشه بالای راست نمایشگر نشان داده خواهد شد. تصویر باید PNG به اندازهٔ ۳۲×۶۴ پیکسل باشد، در غیر این صورت ممکن است لوگو به‌درستی نمایش داده نشود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

آدرس کامل پیوند هیپرمتن برای لوگو را دریافت یا تنظیم می‌کند. فقط در صورتی مؤثر است که یک (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) تعریف شده باشد.

**باز می‌گردد:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

آدرس کامل پیوند هیپرمتن برای لوگو را دریافت یا تنظیم می‌کند. فقط در صورتی مؤثر است که یک (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) تعریف شده باشد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

کیفیت تصاویر JPEG را مشخص می‌کند. به‌طور پیش‌فرض ۹۵ است.

**باز می‌گردد:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

کیفیت تصاویر JPEG را مشخص می‌کند. به‌طور پیش‌فرض ۹۵ است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. این ویژگی از انتساب اشیاء از نوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) پشتیبانی نمی‌کند.

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

**باز می‌گردد:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها روی صفحه هنگام خروجی گرفتن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. این ویژگی از انتساب اشیاء از نوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) پشتیبانی نمی‌کند.

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