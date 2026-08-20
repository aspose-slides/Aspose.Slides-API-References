---
title: IGifOptions
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل خيارات تصدير GIF.
type: docs
url: /ar/com.aspose.slides/igifoptions/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

يمثل خيارات تصدير GIF.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | الحصول على حجم الإطار أو تعيينه. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | الحصول على حجم الإطار أو تعيينه. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | تحديد ما إذا كانت الشرائح المخفية سيتم تصديرها. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | تحديد ما إذا كانت الشرائح المخفية سيتم تصديرها. |
| [getTransitionFps()](#getTransitionFps--) | الحصول على عدد الإطارات في الثانية للانتقال أو تعيينه [frames/sec] القيمة الافتراضية هي 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | الحصول على عدد الإطارات في الثانية للانتقال أو تعيينه [frames/sec] القيمة الافتراضية هي 25. |
| [getDefaultDelay()](#getDefaultDelay--) | الحصول على زمن التأخير الافتراضي أو تعيينه [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | الحصول على زمن التأخير الافتراضي أو تعيينه [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```


الحصول على حجم الإطار أو تعيينه.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**القيمة المرجعة:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```


الحصول على حجم الإطار أو تعيينه.

--------------------

إذا كان الحجم فارغًا فسيتم أخذ القيمة من [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


تحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.

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
public abstract void setExportHiddenSlides(boolean value)
```


تحدد ما إذا كانت الشرائح المخفية سيتم تصديرها. القيمة الافتراضية هي false.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```


الحصول على عدد الإطارات في الثانية للانتقال أو تعيينه [frames/sec] القيمة الافتراضية هي 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


الحصول على عدد الإطارات في الثانية للانتقال أو تعيينه [frames/sec] القيمة الافتراضية هي 25.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


الحصول على زمن التأخير الافتراضي أو تعيينه [ms]. سيتم استخدام هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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
public abstract void setDefaultDelay(int value)
```


الحصول على زمن التأخير الافتراضي أو تعيينه [ms]. سيتم استخدام هذه القيمة إذا لم يتم تعيين [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). القيمة الافتراضية هي 1000.

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |