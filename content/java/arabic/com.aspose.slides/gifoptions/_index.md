---
title: GifOptions
second_title: Aspose.Slides للغة Java مرجع API
description: يمثل خيارات تصدير GIF.
type: docs
url: /ar/com.aspose.slides/gifoptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

يمثل خيارات تصدير GIF.

--------------------

> ```
> المثال التالي يوضح كيفية تحويل العروض التقديمية إلى GIF متحرك باستخدام إعدادات مخصصة.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // حجم الـ GIF الناتج
>      gifOptions.setDefaultDelay(2000); // المدة التي سيُعرض فيها كل شريحة حتى يتم الانتقال إلى التالية
>      gifOptions.setTransitionFps(35); // زيادة معدل الإطارات للحصول على جودة انتقال أفضل
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [GifOptions()](#GifOptions--) | يتهيء مثالًا جديدًا من فئة GifOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | يحصل أو يضبط حجم الإطار. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | يحصل أو يضبط حجم الإطار. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. |
| [getTransitionFps()](#getTransitionFps--) | يحصل أو يضبط معدل الإطارات للانتقال [إطارات/ثانية]. القيمة الافتراضية هي 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | يحصل أو يضبط معدل الإطارات للانتقال [إطارات/ثانية]. القيمة الافتراضية هي 25. |
| [getDefaultDelay()](#getDefaultDelay--) | يحصل أو يضبط وقت التأخير الافتراضي [ملليثانية]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | يحصل أو يضبط وقت التأخير الافتراضي [ملليثانية]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


يتهيء مثالًا جديدًا من فئة GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```


يحصل أو يضبط حجم الإطار.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**القيمة المرجعة:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```


يحصل أو يضبط حجم الإطار.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.

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


**القيمة المرجعة:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


يحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.

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


يحصل أو يضبط معدل الإطارات للانتقال [إطارات/ثانية]. القيمة الافتراضية هي 25.

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

**القيمة المرجعة:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


يحصل أو يضبط معدل الإطارات للانتقال [إطارات/ثانية]. القيمة الافتراضية هي 25.

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


يحصل أو يضبط وقت التأخير الافتراضي [ملليثانية]. ستُستخدم هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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

**القيمة المرجعة:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


يحصل أو يضبط وقت التأخير الافتراضي [ملليثانية]. ستُستخدم هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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