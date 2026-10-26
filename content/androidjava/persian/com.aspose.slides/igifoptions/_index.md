---
title: IGifOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌های صادرات GIF را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/igifoptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

گزینه‌های صادرات GIF را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | اندازه فریم را دریافت یا تنظیم می‌کند. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | اندازه فریم را دریافت یا تنظیم می‌کند. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. |
| [getTransitionFps()](#getTransitionFps--) | FPS انتقال را دریافت یا تنظیم می‌کند [frames/sec] مقدار پیش‌فرض 25 است. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | FPS انتقال را دریافت یا تنظیم می‌کند [frames/sec] مقدار پیش‌فرض 25 است. |
| [getDefaultDelay()](#getDefaultDelay--) | زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

اندازه فریم را دریافت یا تنظیم می‌کند.

--------------------

اگر اندازه خالی باشد، مقدار از [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) گرفته خواهد شد.

**بازگشت:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

اندازه فریم را دریافت یا تنظیم می‌کند.

--------------------

اگر اندازه خالی باشد، مقدار از [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) گرفته خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. مقدار پیش‌فرض false است.

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

تعیین می‌کند که آیا اسلایدهای مخفی صادر شوند یا نه. مقدار پیش‌فرض false است.

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

FPS انتقال را دریافت یا تنظیم می‌کند [frames/sec] مقدار پیش‌فرض 25 است.

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

FPS انتقال را دریافت یا تنظیم می‌کند [frames/sec] مقدار پیش‌فرض 25 است.

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

زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. این مقدار در صورتی استفاده می‌شود که [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) تنظیم نشده باشد. مقدار پیش‌فرض 1000 است.

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

زمان تأخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. این مقدار در صورتی استفاده می‌شود که [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) تنظیم نشده باشد. مقدار پیش‌فرض 1000 است.

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