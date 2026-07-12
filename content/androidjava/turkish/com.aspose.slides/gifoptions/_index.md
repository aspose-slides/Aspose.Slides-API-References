---
title: GifOptions
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: GIF dışa aktarma seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/gifoptions/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

GIF dışa aktarma seçeneklerini temsil eder.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // oluşturulan GIF'in boyutu
>      gifOptions.setDefaultDelay(2000); // her slaytın bir sonraki slayta geçmeden ne kadar süre gösterileceği
>      gifOptions.setTransitionFps(35); // geçiş animasyon kalitesini artırmak için FPS'yi artır
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifOptions()](#GifOptions--) | GifOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Kare boyutunu alır veya ayarlar. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Kare boyutunu alır veya ayarlar. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Gizli slaytların dışa aktarılıp aktarılmayacağını belirler. |
| [getTransitionFps()](#getTransitionFps--) | Geçiş FPS değerini alır veya ayarlar [çerçeve/saniye]. Varsayılan değer 25'tir. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Geçiş FPS değerini alır veya ayarlar [çerçeve/saniye]. Varsayılan değer 25'tir. |
| [getDefaultDelay()](#getDefaultDelay--) | Varsayılan gecikme süresini alır veya ayarlar [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Varsayılan gecikme süresini alır veya ayarlar [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


GifOptions sınıfının yeni bir örneğini başlatır.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


Kare boyutunu alır veya ayarlar.

--------------------

Boyut boşsa, değer [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)'den alınacaktır.

**Döndürür:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```


Kare boyutunu alır veya ayarlar.

--------------------

Boyut boşsa, değer [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)'den alınacaktır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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
public final void setExportHiddenSlides(boolean value)
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
public final int getTransitionFps()
```


Geçiş FPS değerini alır veya ayarlar [çerçeve/saniye]. Varsayılan değer 25'tir.

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
public final void setTransitionFps(int value)
```


Geçiş FPS değerini alır veya ayarlar [çerçeve/saniye]. Varsayılan değer 25'tir.

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
public final int getDefaultDelay()
```


Varsayılan gecikme süresini alır veya ayarlar [ms]. Bu değer [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ayarlanmamışsa kullanılacaktır. Varsayılan değer 1000'dir.

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
public final void setDefaultDelay(int value)
```


Varsayılan gecikme süresini alır veya ayarlar [ms]. Bu değer [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) ayarlanmamışsa kullanılacaktır. Varsayılan değer 1000'dir.

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