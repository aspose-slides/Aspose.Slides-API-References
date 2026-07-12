---
title: SlideShowSettings
second_title: Java API Referansı ile Android için Aspose.Slides
description: Sunum için slayt gösterisi ayarlarını temsil eder.
type: docs
url: /tr/com.aspose.slides/slideshowsettings/
---
**Kalıtım:**
java.lang.Object
```
public class SlideShowSettings
```

Sunum için slayt gösterisi ayarlarını temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Slayt gösterisi türünü alır veya ayarlar. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Slayt gösterisi türünü alır veya ayarlar. |
| [getLoop()](#getLoop--) | Slayt Gösterisini Döngüye Al |
| [setLoop(boolean value)](#setLoop-boolean-) | Slayt Gösterisini Döngüye Al |
| [getShowNarration()](#getShowNarration--) | Slayt Gösterisinde Anlatımı Göster |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Slayt Gösterisinde Anlatımı Göster |
| [getShowAnimation()](#getShowAnimation--) | Slayt Gösterisinde Animasyonu Göster |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Slayt Gösterisinde Animasyonu Göster |
| [getPenColor()](#getPenColor--) | Slayt Gösterisi için Kalem Rengi |
| [getSlides()](#getSlides--) | Slayt aralığı |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Slayt aralığı |
| [getUseTimings()](#getUseTimings--) | Slayt Gösterisinde Zamanlamaları Kullan |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Slayt Gösterisinde Zamanlamaları Kullan |
| [getShowMediaControls()](#getShowMediaControls--) | Medya Kontrollerini Göster |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Medya Kontrolleri

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Slayt gösterisi türünü alır veya ayarlar. Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" tipini ayarlamak için
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" tipini ayarlamak için
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" tipini ayarlamak için
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[SlideShowType](../../com.aspose.slides/slideshowtype)

### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Slayt gösterisi türünü alır veya ayarlar. Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // "Browsed at a kiosk (full screen)" tipini ayarlamak için
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // "Browsed by individual (window)" tipini ayarlamak için
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // "Presented by a speaker (full screen)" tipini ayarlamak için
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Slayt Gösterisini Döngüye Al

**Döndürür:**
boolean

### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Slayt Gösterisini Döngüye Al

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Slayt Gösterisinde Anlatımı Göster

**Döndürür:**
boolean

### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Slayt Gösterisinde Anlatımı Göster

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Slayt Gösterisinde Animasyonu Göster

**Döndürür:**
boolean

### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Slayt Gösterisinde Animasyonu Göster

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Slayt Gösterisi için Kalem Rengi

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Slayt aralığı

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[SlidesRange](../../com.aspose.slides/slidesrange)

### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Slayt aralığı

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SlidesRange slidesRange = new SlidesRange();
>      slidesRange.setStart(1);
>      slidesRange.setEnd(3);
>      pres.getSlideShowSettings().setSlides(slidesRange);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Slayt Gösterisinde Zamanlamaları Kullan

**Döndürür:**
boolean

### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Slayt Gösterisinde Zamanlamaları Kullan

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Medya Kontrollerini Göster

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
boolean

### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Medya Kontrollerini Göster

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |