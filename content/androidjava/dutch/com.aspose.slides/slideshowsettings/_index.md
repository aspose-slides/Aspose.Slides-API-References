---
title: SlideShowSettings
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de diavoorstellingsinstellingen voor de presentatie voor.
type: docs
url: /nl/com.aspose.slides/slideshowsettings/
---
**Erfenis:**
java.lang.Object
```
public class SlideShowSettings
```

Stelt de diavoorstellingsinstellingen voor de presentatie voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Haalt het type diavoorstelling op of stelt het in. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Haalt het type diavoorstelling op of stelt het in. |
| [getLoop()](#getLoop--) | Diavoorstelling herhalen |
| [setLoop(boolean value)](#setLoop-boolean-) | Diavoorstelling herhalen |
| [getShowNarration()](#getShowNarration--) | Vertelling tonen in diavoorstelling |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Vertelling tonen in diavoorstelling |
| [getShowAnimation()](#getShowAnimation--) | Animatie tonen in diavoorstelling |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Animatie tonen in diavoorstelling |
| [getPenColor()](#getPenColor--) | Penkleur voor diavoorstelling |
| [getSlides()](#getSlides--) | Dias bereik |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Dias bereik |
| [getUseTimings()](#getUseTimings--) | Timing gebruiken in diavoorstelling |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Timing gebruiken in diavoorstelling |
| [getShowMediaControls()](#getShowMediaControls--) | Mediabedieningen tonen |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Mediabedieningen tonen |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Haalt het type diavoorstelling op of stelt het in. Gerepresenteerd door de volgende  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) en [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // om type "Browsed at a kiosk (full screen)" in te stellen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // om type "Browsed by individual (window)" in te stellen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // om type "Presented by a speaker (full screen)" in te stellen
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourwaarde:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Haalt het type diavoorstelling op of stelt het in. Gerepresenteerd door de volgende  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) en [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // om type "Browsed at a kiosk (full screen)" in te stellen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // om type "Browsed by individual (window)" in te stellen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // om type "Presented by a speaker (full screen)" in te stellen
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Diavoorstelling herhalen

**Retourwaarde:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Diavoorstelling herhalen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Vertelling tonen in diavoorstelling

**Retourwaarde:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Vertelling tonen in diavoorstelling

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Animatie tonen in diavoorstelling

**Retourwaarde:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Animatie tonen in diavoorstelling

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Penkleur voor diavoorstelling

**Retourwaarde:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Dias bereik

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

**Retourwaarde:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Dias bereik

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Timing gebruiken in diavoorstelling

**Retourwaarde:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Timing gebruiken in diavoorstelling

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Mediabedieningen tonen

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourwaarde:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Mediabedieningen tonen

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |