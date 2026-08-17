---
title: SlideShowSettings
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getSlideShowType()](#getSlideShowType--) | Obtient ou définit le type du diaporama. |
| [setSlideShowType(SlideShowType value)](#setSlideShowType-com.aspose.slides.SlideShowType-) | Obtient ou définit le type du diaporama. |
| [getLoop()](#getLoop--) | Diaporama en boucle |
| [setLoop(boolean value)](#setLoop-boolean-) | Diaporama en boucle |
| [getShowNarration()](#getShowNarration--) | Afficher la narration dans le diaporama |
| [setShowNarration(boolean value)](#setShowNarration-boolean-) | Afficher la narration dans le diaporama |
| [getShowAnimation()](#getShowAnimation--) | Afficher l'animation dans le diaporama |
| [setShowAnimation(boolean value)](#setShowAnimation-boolean-) | Afficher l'animation dans le diaporama |
| [getPenColor()](#getPenColor--) | Couleur du stylo pour le diaporama |
| [getSlides()](#getSlides--) | Plage de diapositives |
| [setSlides(SlidesRange value)](#setSlides-com.aspose.slides.SlidesRange-) | Plage de diapositives |
| [getUseTimings()](#getUseTimings--) | Utiliser les minutages dans le diaporama |
| [setUseTimings(boolean value)](#setUseTimings-boolean-) | Utiliser les minutages dans le diaporama |
| [getShowMediaControls()](#getShowMediaControls--) | Afficher les contrôles multimédias |
| [setShowMediaControls(boolean value)](#setShowMediaControls-boolean-) | Afficher les contrôles multimédias |
### getSlideShowType() {#getSlideShowType--}
```
public final SlideShowType getSlideShowType()
```


Obtient ou définit le type du diaporama. Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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

**Renvoie :**
[SlideShowType](../../com.aspose.slides/slideshowtype)
### setSlideShowType(SlideShowType value) {#setSlideShowType-com.aspose.slides.SlideShowType-}
```
public final void setSlideShowType(SlideShowType value)
```


Obtient ou définit le type du diaporama. Represented by the following  SlideShowType (\#getSlideShowType.getSlideShowType/\#setSlideShowType(SlideShowType).setSlideShowType(SlideShowType)) ancestors: [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk), [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) and [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual)

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


**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlideShowType](../../com.aspose.slides/slideshowtype) |  |

### getLoop() {#getLoop--}
```
public final boolean getLoop()
```


Diaporama en boucle

**Renvoie :**
boolean
### setLoop(boolean value) {#setLoop-boolean-}
```
public final void setLoop(boolean value)
```


Diaporama en boucle

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowNarration() {#getShowNarration--}
```
public final boolean getShowNarration()
```


Afficher la narration dans le diaporama

**Renvoie :**
boolean
### setShowNarration(boolean value) {#setShowNarration-boolean-}
```
public final void setShowNarration(boolean value)
```


Afficher la narration dans le diaporama

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowAnimation() {#getShowAnimation--}
```
public final boolean getShowAnimation()
```


Afficher l'animation dans le diaporama

**Renvoie :**
boolean
### setShowAnimation(boolean value) {#setShowAnimation-boolean-}
```
public final void setShowAnimation(boolean value)
```


Afficher l'animation dans le diaporama

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPenColor() {#getPenColor--}
```
public final IColorFormat getPenColor()
```


Couleur du stylo pour le diaporama

**Renvoie :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getSlides() {#getSlides--}
```
public final SlidesRange getSlides()
```


Plage de diapositives

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


**Renvoie :**
[SlidesRange](../../com.aspose.slides/slidesrange)
### setSlides(SlidesRange value) {#setSlides-com.aspose.slides.SlidesRange-}
```
public final void setSlides(SlidesRange value)
```


Plage de diapositives

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


**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SlidesRange](../../com.aspose.slides/slidesrange) |  |

### getUseTimings() {#getUseTimings--}
```
public final boolean getUseTimings()
```


Utiliser les minutages dans le diaporama

**Renvoie :**
boolean
### setUseTimings(boolean value) {#setUseTimings-boolean-}
```
public final void setUseTimings(boolean value)
```


Utiliser les minutages dans le diaporama

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowMediaControls() {#getShowMediaControls--}
```
public final boolean getShowMediaControls()
```


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

**Renvoie :**
boolean
### setShowMediaControls(boolean value) {#setShowMediaControls-boolean-}
```
public final void setShowMediaControls(boolean value)
```


Afficher les contrôles multimédias

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>     pres.getSlideShowSettings().setShowMediaControls(true);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |