---
title: SlideShowSettings
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt die Folienpräsentationseinstellungen für die Präsentation dar.
type: docs
url: /de/com.aspose.slides/slideshowsettings/
---
**Vererbung:**
java.lang.Object
```
public class SlideShowSettings
```

Stellt die Folienpräsentationseinstellungen für die Präsentation dar.

## Methoden

| Method | Description |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Liest oder legt den SlideShowType fest. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Liest oder legt den SlideShowType fest. |
| [getLoop()](#getLoop--) | Schleifenpräsentation |
| [setLoop(boolean value)](#setLoop-boolean-) | Schleifenpräsentation |
| [getShowNarration()](#getShowNarration--) | Erzählung in der Folienpräsentation anzeigen |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Erzählung in der Folienpräsentation anzeigen |
| [getShowAnimation()](#getShowAnimation--) | Animation in der Folienpräsentation anzeigen |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Animation in der Folienpräsentation anzeigen |
| [getPenColor()](#getPenColor--) | Stiftfarbe für die Folienpräsentation |
| [getSlides()](#getSlides--) | Folienbereich |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Folienbereich |
| [getUseTimings()](#getUseTimings--) | Timing in der Folienpräsentation verwenden |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Timing in der Folienpräsentation verwenden |
| [getShowMediaControls()](#getShowMediaControls--) | Mediensteuerelemente anzeigen |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Mediensteuerelemente anzeigen |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Liest oder legt den SlideShowType fest. Wird durch den folgenden SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) dargestellt, Vorfahren: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) und [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

**Rückgabe:**
[SlideShowType](../../com.aspose.slides/slideshowtype)

### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Liest oder legt den SlideShowType fest. Wird durch den folgenden SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) dargestellt, Vorfahren: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) und [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

Schleifenpräsentation

**Rückgabe:**
boolean

### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Schleifenpräsentation

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Erzählung in der Folienpräsentation anzeigen

**Rückgabe:**
boolean

### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Erzählung in der Folienpräsentation anzeigen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Animation in der Folienpräsentation anzeigen

**Rückgabe:**
boolean

### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Animation in der Folienpräsentation anzeigen

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Stiftfarbe für die Folienpräsentation

**Rückgabe:**
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


**Rückgabe:**
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

Timing in der Folienpräsentation verwenden

**Rückgabe:**
boolean

### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Timing in der Folienpräsentation verwenden

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

**Rückgabe:**
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