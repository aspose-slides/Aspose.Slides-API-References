---
title: HandoutLayoutingOptions
second_title: مرجع API Aspose.Slides برای Java
description: حالت طرح‌بندی ارائه جزوه برای خروجی را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/handoutlayoutingoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

نمایش حالت طرح‌بندی ارائه جزوه برای خروجی.

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | مقادیر پیش‌فرض را مقداردهی اولیه می‌کند. |

## روش‌ها

| متد | توضیح |
| --- | --- |
| [getHandout()](#getHandout--) | مشخص می‌کند چه تعداد اسلاید و به چه ترتیب در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت. |
| [setHandout(int value)](#setHandout-int-) | مشخص می‌کند چه تعداد اسلاید و به چه ترتیب در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت. |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | مشخص می‌کند آیا شماره اسلایدهای نمایش داده شده چاپ شود یا نه. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | مشخص می‌کند آیا شماره اسلایدهای نمایش داده شده چاپ شود یا نه. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | مشخص می‌کند آیا قاب دور اسلایدهای نمایش داده شده رسم شود یا خیر. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | مشخص می‌کند آیا قاب دور اسلایدهای نمایش داده شده رسم شود یا خیر. |
| [getPrintComments()](#getPrintComments--) | مشخص می‌کند آیا نظرات روی اسلایدها نمایش داده شود یا نه |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | مشخص می‌کند آیا نظرات روی اسلایدها نمایش داده شود یا نه |

### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```

مقادیر پیش‌فرض را مقداردهی اولیه می‌کند.

### getHandout() {#getHandout--}
```
public final int getHandout()
```

مشخص می‌کند چه تعداد اسلاید و به چه ترتیب در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **HandoutType.Handouts6Horizontal** .

**بازگشت:**
int

### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```

مشخص می‌کند چه تعداد اسلاید و به چه ترتیب در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **HandoutType.Handouts6Horizontal** .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```

مشخص می‌کند آیا شماره اسلایدهای نمایش داده شده چاپ شود یا نه.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** .

**بازگشت:**
boolean

### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```

مشخص می‌کند آیا شماره اسلایدهای نمایش داده شده چاپ شود یا نه.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```

مشخص می‌کند آیا قاب دور اسلایدهای نمایش داده شده رسم شود یا خیر.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** .

**بازگشت:**
boolean

### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```

مشخص می‌کند آیا قاب دور اسلایدهای نمایش داده شده رسم شود یا خیر.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```

مشخص می‌کند آیا نظرات روی اسلایدها نمایش داده شود یا نه

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **false** .

**بازگشت:**
boolean

### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```

مشخص می‌کند آیا نظرات روی اسلایدها نمایش داده شود یا نه

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **false** .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |