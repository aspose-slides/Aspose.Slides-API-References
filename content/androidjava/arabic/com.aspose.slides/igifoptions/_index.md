---
title: IGifOptions
second_title: Aspose.Slides for Android عبر مرجع API لجافا
description: يمثل خيارات تصدير GIF.
type: docs
url: /ar/com.aspose.slides/igifoptions/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

يمثل خيارات تصدير GIF.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | يحصل على حجم الإطار أو يعيّنه. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | يحصل على حجم الإطار أو يعيّنه. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | يحدّد ما إذا كان سيتم تصدير الشرائح المخفية. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | يحدّد ما إذا كان سيتم تصدير الشرائح المخفية. |
| [getTransitionFps()](#getTransitionFps--) | يحصل أو يعيّن معدل إطارات الانتقال [إطارات/ث] القيمة الافتراضية هي 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | يحصل أو يعيّن معدل إطارات الانتقال [إطارات/ث] القيمة الافتراضية هي 25. |
| [getDefaultDelay()](#getDefaultDelay--) | يحصل أو يعيّن وقت التأخير الافتراضي [مللي ثانية]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | يحصل أو يعيّن وقت التأخير الافتراضي [مللي ثانية]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


يحصل على حجم الإطار أو يعيّنه.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**الإرجاع:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


يحصل على حجم الإطار أو يعيّنه.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


يحدّد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.

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


**الإرجاع:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


يحدّد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.

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


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```


يحصل أو يعيّن معدل إطارات الانتقال [إطارات/ث] القيمة الافتراضية هي 25.

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


**الإرجاع:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


يحصل أو يعيّن معدل إطارات الانتقال [إطارات/ث] القيمة الافتراضية هي 25.

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


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


يحصل أو يعيّن وقت التأخير الافتراضي [مللي ثانية]. سيتم استخدام هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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

**الإرجاع:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```


يحصل أو يعيّن وقت التأخير الافتراضي [مللي ثانية]. سيتم استخدام هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |