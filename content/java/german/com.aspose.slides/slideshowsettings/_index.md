---
title: SlideShowSettings
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Diashow-Einstellungen für die Präsentation dar.
type: docs
url: /de/com.aspose.slides/slideshowsettings/
---
**Vererbung:**
java.lang.Object
```
public class SlideShowSettings
```

Stellt die Diashow-Einstellungen für die Präsentation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Liest oder setzt den Diashowtyp. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Liest oder setzt den Diashowtyp. |
| [getLoop()](#getLoop--) | Diashow wiederholen |
| [setLoop(boolean value)](#setLoop-boolean-) | Diashow wiederholen |
| [getShowNarration()](#getShowNarration--) | Erzählungen in der Diashow anzeigen |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Erzählungen in der Diashow anzeigen |
| [getShowAnimation()](#getShowAnimation--) | Animationen in der Diashow anzeigen |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Animationen in der Diashow anzeigen |
| [getPenColor()](#getPenColor--) | Stiftfarbe für die Diashow |
| [getSlides()](#getSlides--) | Folienbereich |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Folienbereich |
| [getUseTimings()](#getUseTimings--) | Zeitangaben in der Diashow verwenden |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Zeitangaben in der Diashow verwenden |
| [getShowMediaControls()](#getShowMediaControls--) | Mediensteuerelemente anzeigen |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Mediensteuerelemente anzeigen |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


Liest oder setzt den Diashowtyp. Repräsentiert durch den folgenden SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) Vorgänger: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) und [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // um den Typ "Browsed at a kiosk (full screen)" festzulegen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // um den Typ "Browsed by individual (window)" festzulegen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // um den Typ "Presented by a speaker (full screen)" festzulegen
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```


Liest oder setzt den Diashowtyp. Repräsentiert durch den folgenden SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) Vorgänger: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) und [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // um den Typ "Browsed at a kiosk (full screen)" festzulegen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // um den Typ "Browsed by individual (window)" festzulegen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // um den Typ "Presented by a speaker (full screen)" festzulegen
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```


Diashow wiederholen

**Rückgabewert:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```


Diashow wiederholen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```


Erzählungen in der Diashow anzeigen

**Rückgabewert:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```


Erzählungen in der Diashow anzeigen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```


Animationen in der Diashow anzeigen

**Rückgabewert:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```


Animationen in der Diashow anzeigen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```


Stiftfarbe für die Diashow

**Rückgabewert:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```


Folienbereich

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

**Rückgabewert:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```


Folienbereich

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```


Zeitangaben in der Diashow verwenden

**Rückgabewert:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```


Zeitangaben in der Diashow verwenden

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```


Mediensteuerelemente anzeigen

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```


Mediensteuerelemente anzeigen

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |