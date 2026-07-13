---
title: SlideShowSettings
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
description: Reprezentuje ustawienia pokazu slajdów dla prezentacji.
type: docs
url: /pl/com.aspose.slides/slideshowsettings/
---
**Dziedziczenie:**
java.lang.Object
```
public class SlideShowSettings
```

Reprezentuje ustawienia pokazu slajdów dla prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Pobiera lub ustawia typ pokazu slajdów. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Pobiera lub ustawia typ pokazu slajdów. |
| [getLoop()](#getLoop--) | Pętla pokazu slajdów |
| [setLoop(boolean value)](#setLoop-boolean-) | Pętla pokazu slajdów |
| [getShowNarration()](#getShowNarration--) | Pokaż narrację w pokazie slajdów |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Pokaż narrację w pokazie slajdów |
| [getShowAnimation()](#getShowAnimation--) | Pokaż animację w pokazie slajdów |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Pokaż animację w pokazie slajdów |
| [getPenColor()](#getPenColor--) | Kolor pióra dla pokazu slajdów |
| [getSlides()](#getSlides--) | Zakres slajdów |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Zakres slajdów |
| [getUseTimings()](#getUseTimings--) | Użyj synchronizacji w pokazie slajdów |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Użyj synchronizacji w pokazie slajdów |
| [getShowMediaControls()](#getShowMediaControls--) | Pokaż kontrolki multimediów |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Pokaż kontrolki multimediów |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Pobiera lub ustawia typ pokazu slajdów. Reprezentowany przez następujący SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) przodkowie: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) i [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // aby ustawić typ "Browsed at a kiosk (full screen)" 
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // aby ustawić typ "Browsed by individual (window)" 
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // aby ustawić typ "Presented by a speaker (full screen)" 
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Pobiera lub ustawia typ pokazu slajdów. Reprezentowany przez następujący SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) przodkowie: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) i [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // aby ustawić typ "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // aby ustawić typ "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // aby ustawić typ "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Pętla pokazu slajdów

**Zwraca:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Pętla pokazu slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Pokaż narrację w pokazie slajdów

**Zwraca:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Pokaż narrację w pokazie slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Pokaż animację w pokazie slajdów

**Zwraca:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Pokaż animację w pokazie slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Kolor pióra dla pokazu slajdów

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Zakres slajdów

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


**Zwraca:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Zakres slajdów

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Użyj synchronizacji w pokazie slajdów

**Zwraca:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Użyj synchronizacji w pokazie slajdów

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Pokaż kontrolki multimediów

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Pokaż kontrolki multimediów

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |