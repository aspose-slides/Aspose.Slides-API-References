---
title: SlideShowSettings
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa la configuración de la presentación de diapositivas.
type: docs
url: /es/com.aspose.slides/slideshowsettings/
---
**Herencia:**
java.lang.Object
```
public class SlideShowSettings
```

Representa la configuración de la presentación de diapositivas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Obtiene o establece el tipo de presentación de diapositivas. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Obtiene o establece el tipo de presentación de diapositivas. |
| [getLoop()](#getLoop--) | Repetir presentación de diapositivas |
| [setLoop(boolean value)](#setLoop-boolean-) | Repetir presentación de diapositivas |
| [getShowNarration()](#getShowNarration--) | Mostrar narración en la presentación de diapositivas |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Mostrar narración en la presentación de diapositivas |
| [getShowAnimation()](#getShowAnimation--) | Mostrar animación en la presentación de diapositivas |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Mostrar animación en la presentación de diapositivas |
| [getPenColor()](#getPenColor--) | Color del lápiz para la presentación de diapositivas |
| [getSlides()](#getSlides--) | Rango de diapositivas |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Rango de diapositivas |
| [getUseTimings()](#getUseTimings--) | Usar tiempos en la presentación de diapositivas |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Usar tiempos en la presentación de diapositivas |
| [getShowMediaControls()](#getShowMediaControls--) | Mostrar controles de medios |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Mostrar controles de medios |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```

Obtiene o establece el tipo de presentación de diapositivas. Representado por el siguiente SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestros: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) y [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // para establecer el tipo "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // para establecer el tipo "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // para establecer el tipo "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Obtiene o establece el tipo de presentación de diapositivas. Representado por el siguiente SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestros: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) y [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // para establecer el tipo "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // para establecer el tipo "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // para establecer el tipo "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |
### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Repetir presentación de diapositivas

**Devuelve:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Repetir presentación de diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Mostrar narración en la presentación de diapositivas

**Devuelve:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Mostrar narración en la presentación de diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Mostrar animación en la presentación de diapositivas

**Devuelve:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Mostrar animación en la presentación de diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Color del lápiz para la presentación de diapositivas

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Rango de diapositivas

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

**Devuelve:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Rango de diapositivas

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |
### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Usar tiempos en la presentación de diapositivas

**Devuelve:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Usar tiempos en la presentación de diapositivas

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Mostrar controles de medios

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |