---
title: GifOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les options d'exportation GIF.
type: docs
url: /fr/com.aspose.slides/gifoptions/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)  
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Représente les options d'exportation GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // la taille du GIF résultant
>      gifOptions.setDefaultDelay(2000); // durée d'affichage de chaque diapositive avant de passer à la suivante
>      gifOptions.setTransitionFps(35); // augmenter les FPS pour améliorer la qualité de l'animation de transition
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initialise une nouvelle instance de la classe GifOptions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Obtient ou définit la taille du cadre. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Obtient ou définit la taille du cadre. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Détermine si les diapositives masquées seront exportées. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Détermine si les diapositives masquées seront exportées. |
| [getTransitionFps()](#getTransitionFps--) | Obtient ou définit les FPS de transition [frames/sec]. La valeur par défaut est 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Obtient ou définit les FPS de transition [frames/sec]. La valeur par défaut est 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Obtient ou définit le délai par défaut [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Obtient ou définit le délai par défaut [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Initialise une nouvelle instance de la classe GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```

Obtient ou définit la taille du cadre.

--------------------

Si la taille est vide, la valeur sera prise à partir de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Renvoie:**  
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```

Obtient ou définit la taille du cadre.

--------------------

Si la taille est vide, la valeur sera prise à partir de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**  
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Détermine si les diapositives masquées seront exportées. La valeur par défaut est false.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setExportHiddenSlides(false);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

Obtient ou définit les FPS de transition [frames/sec]. La valeur par défaut est 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**  
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Obtient ou définit les FPS de transition [frames/sec]. La valeur par défaut est 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Obtient ou définit le délai par défaut [ms]. Cette valeur sera utilisée si [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) n'est pas définie. La valeur par défaut est 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie:**  
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Obtient ou définit le délai par défaut [ms]. Cette valeur sera utilisée si [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) n'est pas définie. La valeur par défaut est 1000.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setDefaultDelay(2000);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |