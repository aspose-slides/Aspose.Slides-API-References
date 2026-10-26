---
title: ISwfOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب SWF را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/iswfoptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب SWF را کنترل می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getCompressed()](#getCompressed--) | مشخّص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا خیر. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | مشخّص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا خیر. |
| [getViewerIncluded()](#getViewerIncluded--) | مشخّص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | مشخّص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. |
| [getShowPageBorder()](#getShowPageBorder--) | مشخّص می‌کند که آیا مرز دور صفحات نمایش داده شود یا نه. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | مشخّص می‌کند که آیا مرز دور صفحات نمایش داده شود یا نه. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخّص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا خیر. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخّص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا خیر. |
| [getShowFullScreen()](#getShowFullScreen--) | نمایش/پنهان کردن دکمه تمام‌صفحه. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | نمایش/پنهان کردن دکمه تمام‌صفحه. |
| [getShowPageStepper()](#getShowPageStepper--) | نمایش/پنهان کردن مرحله‌ساز صفحه. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | نمایش/پنهان کردن مرحله‌ساز صفحه. |
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
| [getLogoImageBytes()](#getLogoImageBytes--) | تصویری که به‌عنوان لوگو در گوشهٔ بالا-راست نمایشگر نمایش داده می‌شود. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | تصویری که به‌عنوان لوگو در گوشهٔ بالا-راست نمایشگر نمایش داده می‌شود. |
| [getLogoLink()](#getLogoLink--) | آدرس کامل پیوندهایهای‌ابر برای لوگو را دریافت یا تنظیم می‌کند. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | آدرس کامل پیوندهایهای‌ابر برای لوگو را دریافت یا تنظیم می‌کند. |
| [getJpegQuality()](#getJpegQuality--) | کیفیت تصاویر JPEG را مشخص می‌کند. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | کیفیت تصاویر JPEG را مشخص می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها روی صفحه هنگام برون‌ریزی ارائهٔ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها روی صفحه هنگام برون‌ریزی ارائهٔ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

مشخّص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا خیر. پیش‌فرض true است.

**بازگشت:**  
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

مشخّص می‌کند که آیا سند SWF تولید شده باید فشرده شود یا خیر. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

مشخّص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. پیش‌فرض true است.

**بازگشت:**  
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

مشخّص می‌کند که آیا سند SWF تولید شده باید نمایشگر سند یکپارچه را شامل شود یا خیر. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

مشخّص می‌کند که آیا مرز دور صفحات نمایش داده شود یا نه. پیش‌فرض true است.

**بازگشت:**  
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

مشخّص می‌کند که آیا مرز دور صفحات نمایش داده شود یا نه. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

مشخّص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا خیر. پیش‌فرض false است.

**بازگشت:**  
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

مشخّص می‌کند که آیا سند تولید شده اسلایدهای مخفی را شامل شود یا خیر. پیش‌فرض false است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

نمایش/پنهان کردن دکمه تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**بازگشت:**  
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

نمایش/پنهان کردن دکمه تمام‌صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

نمایش/پنهان کردن مرحله‌ساز صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**بازگشت:**  
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

نمایش/پنهان کردن مرحله‌ساز صفحه. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

نمایش/پنهان کردن بخش جستجو. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**بازگشت:**  
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

نمایش/پنهان کردن بخش جستجو. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

نمایش/پنهان کردن تمام نوار بالایی. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**بازگشت:**  
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

نمایش/پنهان کردن تمام نوار بالایی. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

نمایش/پنهان کردن نوار پایین. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**بازگشت:**  
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

نمایش/پنهان کردن نوار پایین. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

نمایش/پنهان کردن نوار چپ. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**بازگشت:**  
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

نمایش/پنهان کردن نوار چپ. می‌تواند در flashvars بازنویسی شود. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

شروع با نوار چپ باز. می‌تواند در flashvars بازنویسی شود. پیش‌فرض false است.

**بازگشت:**  
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

شروع با نوار چپ باز. می‌تواند در flashvars بازنویسی شود. پیش‌فرض false است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

فعال/غیرفعال کردن منوی زمینه. پیش‌فرض true است.

**بازگشت:**  
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

فعال/غیرفعال کردن منوی زمینه. پیش‌فرض true است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

تصویری که به‌عنوان لوگو در گوشهٔ بالا-راست نمایشگر نمایش داده می‌شود. تصویر باید PNG با ابعاد ۳۲×۶۴ پیکسل باشد؛ در غیر این صورت ممکن است لوگو به‌درستی نمایش داده نشود.

**بازگشت:**  
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

تصویری که به‌عنوان لوگو در گوشهٔ بالا-راست نمایشگر نمایش داده می‌شود. تصویر باید PNG با ابعاد ۳۲×۶۴ پیکسل باشد؛ در غیر این صورت ممکن است لوگو به‌درستی نمایش داده نشود.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

آدرس کامل پیوندهایهای‌ابر برای لوگو را دریافت یا تنظیم می‌کند. فقط در صورتی مؤثر است که (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) مشخص شود.

**بازگشت:**  
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

آدرس کامل پیوندهایهای‌ابر برای لوگو را دریافت یا تنظیم می‌کند. فقط در صورتی مؤثر است که (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) مشخص شود.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

کیفیت تصاویر JPEG را مشخص می‌کند. پیش‌فرض ۹۵ است.

**بازگشت:**  
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

کیفیت تصاویر JPEG را مشخص می‌کند. پیش‌فرض ۹۵ است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها روی صفحه هنگام برون‌ریزی ارائهٔ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) پشتیبانی نمی‌کند.

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها روی صفحه هنگام برون‌ریزی ارائهٔ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. این ویژگی از اختصاص اشیاء از نوع [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) پشتیبانی نمی‌کند.

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