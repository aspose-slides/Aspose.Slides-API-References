---
title: SlideShowSettings
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le impostazioni della presentazione.
type: docs
url: /it/com.aspose.slides/slideshowsettings/
---
**Eredità:**
java.lang.Object
```
public class SlideShowSettings
```

Rappresenta le impostazioni della presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Recupera o imposta il tipo di presentazione. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Recupera o imposta il tipo di presentazione. |
| [getLoop()](#getLoop--) | Presentazione in loop |
| [setLoop(boolean value)](#setLoop-boolean-) | Presentazione in loop |
| [getShowNarration()](#getShowNarration--) | Mostra narrazione nella presentazione |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Mostra narrazione nella presentazione |
| [getShowAnimation()](#getShowAnimation--) | Mostra animazione nella presentazione |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Mostra animazione nella presentazione |
| [getPenColor()](#getPenColor--) | Colore penna per la presentazione |
| [getSlides()](#getSlides--) | Intervallo di diapositive |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Intervallo di diapositive |
| [getUseTimings()](#getUseTimings--) | Usa tempi nella presentazione |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Usa tempi nella presentazione |
| [getShowMediaControls()](#getShowMediaControls--) | Mostra controlli multimediali |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Mostra controlli multimediali |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Recupera o imposta il tipo di presentazione. Rappresentato dal seguente SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) antenati: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) e [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // per impostare il tipo "Navigazione a chiosco (schermo intero)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // per impostare il tipo "Navigazione da individuo (finestra)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // per impostare il tipo "Presentato da un relatore (schermo intero)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Recupera o imposta il tipo di presentazione. Rappresentato dal seguente SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) antenati: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) e [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // per impostare il tipo "Navigazione a chiosco (schermo intero)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // per impostare il tipo "Navigazione da individuo (finestra)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // per impostare il tipo "Presentato da un relatore (schermo intero)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |
### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Presentazione in loop

**Restituisce:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Presentazione in loop

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Mostra narrazione nella presentazione

**Restituisce:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Mostra narrazione nella presentazione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Mostra animazione nella presentazione

**Restituisce:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Mostra animazione nella presentazione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Colore penna per la presentazione

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Intervallo di diapositive

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


**Restituisce:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Intervallo di diapositive

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |
### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Usa tempi nella presentazione

**Restituisce:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Usa tempi nella presentazione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |
### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Mostra controlli multimediali

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

Mostra controlli multimediali

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |