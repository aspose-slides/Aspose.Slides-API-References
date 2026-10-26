---
title: IGifOptions
second_title: Aspose.Slides Android için Java API Referansı
description: GIF dışa aktarma seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/igifoptions/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

GIF dışa aktarma seçeneklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | çerçeve boyutunu alır veya ayarlar. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | çerçeve boyutunu alır veya ayarlar. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. |
| [getTransitionFps()](#getTransitionFps--) | Geçiş FPS'sini (kare/sn) alır veya ayarlar. Varsayılan değer 25'tir. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Geçiş FPS'sini (kare/sn) alır veya ayarlar. Varsayılan değer 25'tir. |
| [getDefaultDelay()](#getDefaultDelay--) | Varsayılan gecikme süresini (ms) alır veya ayarlar. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Varsayılan gecikme süresini (ms) alır veya ayarlar. |

### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

Çerçeve boyutunu alır veya ayarlar.

--------------------

Boyut boşsa, değer [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)'den alınacaktır.

**Döndürür:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

Çerçeve boyutunu alır veya ayarlar.

--------------------

Boyut boşsa, değer [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)'den alınacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.

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

**Döndürür:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. Varsayılan değer false'tur.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Geçiş FPS'sini (kare/sn) alır veya ayarlar. Varsayılan değer 25'tir.

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

**Döndürür:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

Geçiş FPS'sini (kare/sn) alır veya ayarlar. Varsayılan değer 25'tir.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Varsayılan gecikme süresini (ms) alır veya ayarlar. Bu değer [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ayarlı değilse kullanılacaktır. Varsayılan değer 1000'tir.

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

**Döndürür:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

Varsayılan gecikme süresini (ms) alır veya ayarlar. Bu değer [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ayarlı değilse kullanılacaktır. Varsayılan değer 1000'tir.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |