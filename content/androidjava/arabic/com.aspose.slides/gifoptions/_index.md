---
title: GifOptions
second_title: Aspose.Slides للـ Android عبر مرجع API Java
description: يمثل خيارات تصدير GIF.
type: docs
url: /ar/com.aspose.slides/gifoptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

يمثل خيارات تصدير GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // حجم الـ GIF الناتج
>      gifOptions.setDefaultDelay(2000); // المدة التي سيظهر فيها كل شريحة قبل الانتقال إلى التالية
>      gifOptions.setTransitionFps(35); // زيادة FPS لتحسين جودة حركة الانتقال
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [GifOptions()](#GifOptions--) | يهيئ نسخة جديدة من الفئة GifOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | يحصل أو يضبط حجم الإطار. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | يحصل أو يضبط حجم الإطار. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | يحدد ما إذا كان سيتم تصدير الشرائح المخفية. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | يحدد ما إذا كان سيتم تصدير الشرائح المخفية. |
| [getTransitionFps()](#getTransitionFps--) | يحصل أو يضبط FPS الانتقال [إطارات/ث]. القيمة الافتراضية هي 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | يحصل أو يضبط FPS الانتقال [إطارات/ث]. القيمة الافتراضية هي 25. |
| [getDefaultDelay()](#getDefaultDelay--) | يحصل أو يضبط وقت التأخير الافتراضي [ملس]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | يحصل أو يضبط وقت التأخير الافتراضي [ملس]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


يقوم بتهيئة نسخة جديدة من الفئة GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


يحصل أو يضبط حجم الإطار.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**الإرجاع:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```


يحصل أو يضبط حجم الإطار.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


يحدد ما إذا كان سيتم تصدير الشرائح المخفية. القيمة الافتراضية هي false.

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
public final void setExportHiddenSlides(boolean value)
```


يحدد ما إذا كان سيتم تصدير الشرائح المخفية. القيمة الافتراضية هي false.

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
public final int getTransitionFps()
```


يحصل أو يضبط FPS الانتقال [إطارات/ث]. القيمة الافتراضية هي 25.

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
public final void setTransitionFps(int value)
```


يحصل أو يضبط FPS الانتقال [إطارات/ث]. القيمة الافتراضية هي 25.

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
public final int getDefaultDelay()
```


يحصل أو يضبط وقت التأخير الافتراضي [ملس]. سيتم استخدام هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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
public final void setDefaultDelay(int value)
```


يحصل أو يضبط وقت التأخير الافتراضي [ملس]. سيتم استخدام هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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