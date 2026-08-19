---
title: GifOptions
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر گزینه‌های صادرات GIF است.
type: docs
url: /fa/com.aspose.slides/gifoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

نمایانگر گزینه‌های صادرات GIF است.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // اندازهٔ GIF تولید شده
>      gifOptions.setDefaultDelay(2000); // مدت زمان نمایش هر اسلاید تا زمانی که به اسلاید بعدی تغییر کند
>      gifOptions.setTransitionFps(35); // افزایش FPS برای بهبود کیفیت انیمیشن انتقال
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [GifOptions()](#GifOptions--) | یک نمونه جدید از کلاس GifOptions را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | اندازه فریم را دریافت یا تنظیم می‌کند. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | اندازه فریم را دریافت یا تنظیم می‌کند. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند. |
| [getTransitionFps()](#getTransitionFps--) | FPS انتقال را دریافت یا تنظیم می‌کند [فریم/ثانیه] مقدار پیش‌فرض ۲۵ است. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | FPS انتقال را دریافت یا تنظیم می‌کند [فریم/ثانیه] مقدار پیش‌فرض ۲۵ است. |
| [getDefaultDelay()](#getDefaultDelay--) | زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [میلی‌ثانیه]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [میلی‌ثانیه]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

یک نمونه جدید از کلاس GifOptions را مقداردهی اولیه می‌کند.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

اندازه فریم را دریافت یا تنظیم می‌کند.

--------------------

اگر اندازه خالی باشد، مقدار از [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) گرفته خواهد شد.

**بازگشت:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

اندازه فریم را دریافت یا تنظیم می‌کند.

--------------------

اگر اندازه خالی باشد، مقدار از [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) گرفته خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

تعیین می‌کند آیا اسلایدهای مخفی صادر شوند. مقدار پیش‌فرض false است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

تعیین می‌کند آیا اسلایدهای مخفی صادر شوند. مقدار پیش‌فرض false است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

FPS انتقال را دریافت یا تنظیم می‌کند [فریم/ثانیه] مقدار پیش‌فرض ۲۵ است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

FPS انتقال را دریافت یا تنظیم می‌کند [فریم/ثانیه] مقدار پیش‌فرض ۲۵ است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [میلی‌ثانیه]. این مقدار در صورتی استفاده می‌شود که [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) تنظیم نشده باشد. مقدار پیش‌فرض ۱۰۰۰ است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [میلی‌ثانیه]. این مقدار در صورتی استفاده می‌شود که [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) تنظیم نشده باشد. مقدار پیش‌فرض ۱۰۰۰ است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |