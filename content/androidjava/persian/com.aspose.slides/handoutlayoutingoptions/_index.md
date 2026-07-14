---
title: HandoutLayoutingOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر حالت چیدمان ارائه برگه برای خروجی.
type: docs
url: /fa/com.aspose.slides/handoutlayoutingoptions/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

نمایانگر حالت چیدمان ارائهٔ برگه برای خروجی است.
## سازنده‌ها

| Constructor | Description |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | مقادیر پیش‌فرض را مقداردهی اولیه می‌کند. |
## متدها

| Method | Description |
| --- | --- |
| [getHandout()](#getHandout--) | تعیین می‌کند که چند اسلاید و به چه ترتیبی در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت. |
| [setHandout(int value)](#setHandout-int-) | تعیین می‌کند که چند اسلاید و به چه ترتیبی در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت. |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | تعیین می‌کند که آیا شماره‌های اسلاید نمایش‌داده‌شده چاپ شود یا نه. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | تعیین می‌کند که آیا شماره‌های اسلاید نمایش‌داده‌شده چاپ شود یا نه. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | تعیین می‌کند که آیا قاب‌ها دور اسلایدهای نمایش‌داده‌شده کشیده شوند یا نه. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | تعیین می‌کند که آیا قاب‌ها دور اسلایدهای نمایش‌داده‌شده کشیده شوند یا نه. |
| [getPrintComments()](#getPrintComments--) | تعیین می‌کند که آیا نظرات روی اسلایدها نمایش داده شوند یا نه |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | تعیین می‌کند که آیا نظرات روی اسلایدها نمایش داده شوند یا نه |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```


مقادیر پیش‌فرض را مقداردهی اولیه می‌کند.

### getHandout() {#getHandout--}
```
public final int getHandout()
```


تعیین می‌کند که چند اسلاید و به چه ترتیبی در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **HandoutType.Handouts6Horizontal** است.

**بازگشت:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```


تعیین می‌کند که چند اسلاید و به چه ترتیبی در صفحه [HandoutType](../../com.aspose.slides/handouttype) قرار خواهند گرفت.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **HandoutType.Handouts6Horizontal** است.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```


تعیین می‌کند که آیا شماره‌های اسلاید نمایش‌داده‌شده چاپ شود یا نه.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** است.

**بازگشت:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```


تعیین می‌کند که آیا شماره‌های اسلاید نمایش‌داده‌شده چاپ شود یا نه.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** است.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```


تعیین می‌کند که آیا قاب‌ها دور اسلایدهای نمایش‌داده‌شده کشیده شوند یا نه.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** است.

**بازگشت:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```


تعیین می‌کند که آیا قاب‌ها دور اسلایدهای نمایش‌داده‌شده کشیده شوند یا نه.

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **true** است.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```


تعیین می‌کند که آیا نظرات روی اسلایدها نمایش داده شوند یا نه

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **false** است.

**بازگشت:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```


تعیین می‌کند که آیا نظرات روی اسلایدها نمایش داده شوند یا نه

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
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

مقدار پیش‌فرض **false** است.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |