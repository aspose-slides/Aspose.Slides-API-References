---
title: SlideShowSettings
second_title: Aspose.Slides Android számára Java API hivatkozás alapján
description: A prezentáció diavetítés beállításait képviseli.
type: docs
url: /hu/com.aspose.slides/slideshowsettings/
---
**Inheritance:**
java.lang.Object
```
public class SlideShowSettings
```

A prezentáció diavetítés beállításait képviseli.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Lekéri vagy beállítja a diavetítés típusát. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Lekéri vagy beállítja a diavetítés típusát. |
| [getLoop()](#getLoop--) | Ismétlődő diavetítés |
| [setLoop(boolean value)](#setLoop-boolean-) | Ismétlődő diavetítés |
| [getShowNarration()](#getShowNarration--) | Narráció megjelenítése a diavetítésben |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Narráció megjelenítése a diavetítésben |
| [getShowAnimation()](#getShowAnimation--) | Animáció megjelenítése a diavetítésben |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Animáció megjelenítése a diavetítésben |
| [getPenColor()](#getPenColor--) | Toll színe a diavetítéshez |
| [getSlides()](#getSlides--) | Diák tartománya |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Diák tartománya |
| [getUseTimings()](#getUseTimings--) | Időzítések használata a diavetítésben |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Időzítések használata a diavetítésben |
| [getShowMediaControls()](#getShowMediaControls--) | Médiavezérlők megjelenítése |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Médiavezérlők megjelenítése |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Lekéri vagy beállítja a diavetítés típusát. A következő SlideShowType által reprezentált (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ősök: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) és [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

Lekéri vagy beállítja a diavetítés típusát. A következő SlideShowType által reprezentált (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ősök: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) és [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

Ismétlődő diavetítés

**Visszatérési érték:**
boolean

### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Ismétlődő diavetítés

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

Toll színe a diavetítéshez

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Diák tartománya

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

Diák tartománya

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