---
title: SlideShowSettings
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar bildspelsinställningarna för presentationen.
type: docs
url: /sv/com.aspose.slides/slideshowsettings/
---
**Arv:**
java.lang.Object
```
public class SlideShowSettings
```

Representerar bildspelsinställningarna för presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Hämtar eller ställer in bildspels-typen. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Hämtar eller ställer in bildspels-typen. |
| [getLoop()](#getLoop--) | Upprepa bildspel |
| [setLoop(boolean value)](#setLoop-boolean-) | Upprepa bildspel |
| [getShowNarration()](#getShowNarration--) | Visa berättelse i bildspel |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Visa berättelse i bildspel |
| [getShowAnimation()](#getShowAnimation--) | Visa animation i bildspel |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Visa animation i bildspel |
| [getPenColor()](#getPenColor--) | Penfärg för bildspel |
| [getSlides()](#getSlides--) | Bildspelsintervall |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Bildspelsintervall |
| [getUseTimings()](#getUseTimings--) | Använd tidsinställningar i bildspel |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Använd tidsinställningar i bildspel |
| [getShowMediaControls()](#getShowMediaControls--) | Visa mediekontroller |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Visa mediekontroller |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


Hämtar eller ställer in bildspels-typen. Representeras av följande SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) förfäder: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) och [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // för att sätta "Browsed at a kiosk (full screen)"-typen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // för att sätta "Browsed by individual (window)"-typen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // för att sätta "Presented by a speaker (full screen)"-typen
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```


Hämtar eller ställer in bildspels-typen. Representeras av följande SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) förfäder: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) och [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // för att sätta "Browsed at a kiosk (full screen)"-typen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // för att sätta "Browsed by individual (window)"-typen
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // för att sätta "Presented by a speaker (full screen)"-typen
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```


Upprepa bildspel

**Returnerar:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```


Upprepa bildspel

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```


Visa berättelse i bildspel

**Returnerar:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```


Visa berättelse i bildspel

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```


Visa animation i bildspel

**Returnerar:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```


Visa animation i bildspel

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```


Penfärg för bildspel

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```


Bildspelsintervall

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

**Returnerar:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```


Bildspelsintervall

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

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```


Använd tidsinställningar i bildspel

**Returnerar:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```


Använd tidsinställningar i bildspel

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```


Visa mediekontroller

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```


Visa mediekontroller

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |