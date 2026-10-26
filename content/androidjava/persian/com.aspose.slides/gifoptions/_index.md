---
title: GifOptions
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر گزینه‌های خروجی GIF است.
type: docs
url: /fa/com.aspose.slides/gifoptions/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)  
```
public class GifOptions extends SaveOptions implements IGifOptions
```

نمایانگر گزینه‌های خروجی GIF است.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // اندازه GIF تولید شده
>      gifOptions.setDefaultDelay(2000); // مدت زمانی که هر اسلاید نمایش داده می‌شود تا به اسلاید بعدی تغییر کند
>      gifOptions.setTransitionFps(35); // FPS را برای بهبود کیفیت انیمیشن انتقال افزایش دهید
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
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | اندازه فریم را دریافت یا تنظیم می‌کند. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا خیر. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا خیر. |
| [getTransitionFps()](#getTransitionFps--) | دریافت یا تنظیم FPS انتقال [frames/sec] مقدار پیش‌فرض ۲۵ است. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | دریافت یا تنظیم FPS انتقال [frames/sec] مقدار پیش‌فرض ۲۵ است. |
| [getDefaultDelay()](#getDefaultDelay--) | زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. |

### GifOptions() {#GifOptions--}
```
public GifOptions()
```

یک نمونه جدید از کلاس GifOptions را مقداردهی اولیه می‌کند.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

اندازه فریم را دریافت یا تنظیم می‌کند.

--------------------

اگر اندازه خالی باشد، مقدار از [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize) گرفته خواهد شد.

**بازگشت:**  
[Size](../../com.aspose.slides.android/size)

### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
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
public final boolean getExportHiddenSlides()
```

تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا خیر. مقدار پیش‌فرض false است.

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

تعیین می‌کند آیا اسلایدهای مخفی صادر شوند یا خیر. مقدار پیش‌فرض false است.

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

FPS انتقال را دریافت یا تنظیم می‌کند [frames/sec] مقدار پیش‌فرض ۲۵ است.

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

FPS انتقال را دریافت یا تنظیم می‌کند [frames/sec] مقدار پیش‌فرض ۲۵ است.

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

زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. این مقدار در صورتی که [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) تنظیم نشده باشد استفاده می‌شود. مقدار پیش‌فرض ۱۰۰۰ است.

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

زمان تاخیر پیش‌فرض را دریافت یا تنظیم می‌کند [ms]. این مقدار در صورتی که [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) تنظیم نشده باشد استفاده می‌شود. مقدار پیش‌فرض ۱۰۰۰ است.

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