---
title: IGifOptions
second_title: مرجع API Aspose.Slides برای Java
description: گزینه‌های خروجی GIF را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/igifoptions/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

گزینه‌های خروجی GIF را نشان می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | اندازه فریم را دریافت یا تنظیم می‌کند. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | اندازه فریم را دریافت یا تنظیم می‌کند. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | تعیین می‌کند آیا اسلایدهای مخفی صادر می‌شوند یا نه. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | تعیین می‌کند آیا اسلایدهای مخفی صادر می‌شوند یا نه. |
| [getTransitionFps()](#getTransitionFps--) | FPS انتقال را دریافت یا تنظیم می‌کند [قاب/ثانیه] مقدار پیش‌فرض ۲۵ است. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | FPS انتقال را دریافت یا تنظیم می‌کند [قاب/ثانیه] مقدار پیش‌فرض ۲۵ است. |
| [getDefaultDelay()](#getDefaultDelay--) | زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```

اندازه فریم را دریافت یا تنظیم می‌کند.

--------------------

اگر اندازه خالی باشد، مقدار از [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) گرفته خواهد شد

**بازگشت:**  
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```

اندازه فریم را دریافت یا تنظیم می‌کند.

--------------------

اگر اندازه خالی باشد، مقدار از [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) گرفته خواهد شد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

تعیین می‌کند آیا اسلایدهای مخفی صادر می‌شوند یا نه. مقدار پیش‌فرض false است.

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
public abstract void setExportHiddenSlides(boolean value)
```

تعیین می‌کند آیا اسلایدهای مخفی صادر می‌شوند یا نه. مقدار پیش‌فرض false است.

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
public abstract int getTransitionFps()
```

FPS انتقال را دریافت یا تنظیم می‌کند [قاب/ثانیه] مقدار پیش‌فرض ۲۵ است.

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
public abstract void setTransitionFps(int value)
```

FPS انتقال را دریافت یا تنظیم می‌کند [قاب/ثانیه] مقدار پیش‌فرض ۲۵ است.

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
public abstract int getDefaultDelay()
```

زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. این مقدار در صورت عدم تنظیم [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) استفاده خواهد شد. مقدار پیش‌فرض ۱۰۰۰ است.

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
public abstract void setDefaultDelay(int value)
```

زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. این مقدار در صورت عدم تنظیم [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) استفاده خواهد شد. مقدار پیش‌فرض ۱۰۰۰ است.

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