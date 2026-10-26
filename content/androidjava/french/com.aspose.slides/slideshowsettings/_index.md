---
title: SlideShowSettings
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente les paramètres du diaporama pour la présentation.
type: docs
url: /fr/com.aspose.slides/slideshowsettings/
---
**Héritage :**
java.lang.Object
```
public class SlideShowSettings
```

Représente les paramètres du diaporama pour la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSlideShowType()](#getSlideShowType--) | Obtient ou définit le type de diaporama. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Obtient ou définit le type de diaporama. |
| [getLoop()](#getLoop--) | Boucler le diaporama |
| [setLoop(boolean value)](#setLoop-boolean-) | Boucler le diaporama |
| [getShowNarration()](#getShowNarration--) | Afficher la narration dans le diaporama |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Afficher la narration dans le diaporama |
| [getShowAnimation()](#getShowAnimation--) | Afficher les animations dans le diaporama |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Afficher les animations dans le diaporama |
| [getPenColor()](#getPenColor--) | Couleur du stylet pour le diaporama |
| [getSlides()](#getSlides--) | Plage de diapositives |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Plage de diapositives |
| [getUseTimings()](#getUseTimings--) | Utiliser les minuteries dans le diaporama |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Utiliser les minuteries dans le diaporama |
| [getShowMediaControls()](#getShowMediaControls--) | Afficher les contrôles multimédias |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Afficher les contrôles multimédias |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


Obtient ou définit le type de diaporama. Représenté par le SlideShowType suivant (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancêtres : [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) et [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // to set "Browsed at a kiosk (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // to set "Browsed by individual (window)" type
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // to set "Presented by a speaker (full screen)" type
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```

Gets or sets the slide show type. Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      // pour définir le type "Browsed at a kiosk (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
> 
>      // pour définir le type "Browsed by individual (window)"
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
> 
>      // pour définir le type "Presented by a speaker (full screen)"
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```

Loop Slide Show

**Returns:**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```

Loop Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```

Show Narration in Slide Show

**Returns:**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```

Show Narration in Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```

Show Animation in Slide Show

**Returns:**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```

Show Animation in Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```

Pen Color for Slide Show

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```

Slides range

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

**Returns:**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```

Slides range

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```

Use Timings in Slide Show

**Returns:**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```

Use Timings in Slide Show

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```

Show Media Controls

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)


Afficher les contrôles multimédias

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |