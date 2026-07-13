---
title: SlideShowSettings
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje nastavení prezentace.
type: docs
url: /cs/com.aspose.slides/slideshowsettings/
---
**Dědičnost:**
java.lang.Object
```
public class SlideShowSettings
```

Representuje nastavení prezentace.

## Metody

| Metoda | Popis |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Získává nebo nastavuje typ prezentace. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Získává nebo nastavuje typ prezentace. |
| [getLoop()](#getLoop--) | Opakovat prezentaci |
| [setLoop(boolean value)](#setLoop-boolean-) | Opakovat prezentaci |
| [getShowNarration()](#getShowNarration--) | Zobrazit komentář v prezentaci |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Zobrazit komentář v prezentaci |
| [getShowAnimation()](#getShowAnimation--) | Zobrazit animaci v prezentaci |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Zobrazit animaci v prezentaci |
| [getPenColor()](#getPenColor--) | Barva pera pro prezentaci |
| [getSlides()](#getSlides--) | Rozsah snímků |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Rozsah snímků |
| [getUseTimings()](#getUseTimings--) | Použít časování v prezentaci |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Použít časování v prezentaci |
| [getShowMediaControls()](#getShowMediaControls--) | Zobrazit ovládací prvky médií |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Zobrazit ovládací prvky médií |

### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Získává nebo nastavuje typ prezentace. Reprezentováno následujícím SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) předky: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) a [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // pro nastavení typu "Browsed at a kiosk (full screen)" 
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // pro nastavení typu "Browsed by individual (window)" 
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // pro nastavení typu "Presented by a speaker (full screen)" 
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
[SlideShowType](../../com.aspose.slides/slideshowtype)

### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Získává nebo nastavuje typ prezentace. Reprezentováno následujícím SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) předky: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) a [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // pro nastavení typu "Browsed at a kiosk (full screen)" 
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // pro nastavení typu "Browsed by individual (window)" 
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // pro nastavení typu "Presented by a speaker (full screen)" 
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Opakovat prezentaci

**Vrací:**
boolean

### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Opakovat prezentaci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Zobrazit komentář v prezentaci

**Vrací:**
boolean

### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Zobrazit komentář v prezentaci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Zobrazit animaci v prezentaci

**Vrací:**
boolean

### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Zobrazit animaci v prezentaci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Barva pera pro prezentaci

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Rozsah snímků

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

**Vrací:**
[SlidesRange](../../com.aspose.slides/slidesrange)

### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Rozsah snímků

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Použít časování v prezentaci

**Vrací:**
boolean

### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Použít časování v prezentaci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Zobrazit ovládací prvky médií

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
boolean

### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Zobrazit ovládací prvky médií

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |