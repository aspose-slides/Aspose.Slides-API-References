---
title: SlideShowSettings
second_title: Aspose.Slides a Java API referencia
description: A diavetítés beállításait képviseli a bemutatóhoz.
type: docs
url: /hu/com.aspose.slides/slideshowsettings/
---
**Öröklés:**
java.lang.Object
```
public class SlideShowSettings
```

A diavetítés beállításait képviseli a bemutatóhoz.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | A diavetítés típusát lekéri vagy beállítja. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | A diavetítés típusát lekéri vagy beállítja. |
| [getLoop()](#getLoop--) | Diavetítés ismétlése |
| [setLoop(boolean value)](#setLoop-boolean-) | Diavetítés ismétlése |
| [getShowNarration()](#getShowNarration--) | Narráció megjelenítése a diavetítésben |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Narráció megjelenítése a diavetítésben |
| [getShowAnimation()](#getShowAnimation--) | Animáció megjelenítése a diavetítésben |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Animáció megjelenítése a diavetítésben |
| [getPenColor()](#getPenColor--) | A ceruza színe a diavetítéshez |
| [getSlides()](#getSlides--) | Dia tartomány |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Dia tartomány |
| [getUseTimings()](#getUseTimings--) | Időzítések használata a diavetítésben |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Időzítések használata a diavetítésben |
| [getShowMediaControls()](#getShowMediaControls--) | Médiavezérlők megjelenítése |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Médiavezérlők megjelenítése |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

A diavetítés típusát lekéri vagy beállítja. A következő SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ősei: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) és [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // a "Browsed at a kiosk (full screen)" típus beállításához
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // a "Browsed by individual (window)" típus beállításához
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // a "Presented by a speaker (full screen)" típus beállításához
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

A diavetítés típusát lekéri vagy beállítja. A következő SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ősei: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) és [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // a "Browsed at a kiosk (full screen)" típus beállításához
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // a "Browsed by individual (window)" típus beállításához
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // a "Presented by a speaker (full screen)" típus beállításához
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Diavetítés ismétlése

**Visszatérési érték:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Diavetítés ismétlése

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Narráció megjelenítése a diavetítésben

**Visszatérési érték:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Narráció megjelenítése a diavetítésben

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Animáció megjelenítése a diavetítésben

**Visszatérési érték:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Animáció megjelenítése a diavetítésben

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

A ceruza színe a diavetítéshez

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Dia tartomány

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

**Visszatérési érték:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Dia tartomány

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Időzítések használata a diavetítésben

**Visszatérési érték:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Időzítések használata a diavetítésben

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Médiavezérlők megjelenítése

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Médiavezérlők megjelenítése

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |