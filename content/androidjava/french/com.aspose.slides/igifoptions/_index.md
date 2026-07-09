---
title: IGifOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente les options d'exportation GIF.
type: docs
url: /fr/com.aspose.slides/igifoptions/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Représente les options d'exportation GIF.  
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Obtient ou définit la taille du cadre. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Obtient ou définit la taille du cadre. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Détermine si les diapositives cachées seront exportées. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Détermine si les diapositives cachées seront exportées. |
| [getTransitionFps()](#getTransitionFps--) | Obtient ou définit le FPS de transition [frames/sec]. La valeur par défaut est 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Obtient ou définit le FPS de transition [frames/sec]. La valeur par défaut est 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Obtient ou définit le délai par défaut [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Obtient ou définit le délai par défaut [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

Obtient ou définit la taille du cadre.

--------------------

Si la taille est vide, la valeur sera prise à partir de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Renvoie :**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

Obtient ou définit la taille du cadre.

--------------------

Si la taille est vide, la valeur sera prise à partir de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Détermine si les diapositives cachées seront exportées. La valeur par défaut est false.

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

**Returns:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Determines whether hidden slides will be exported. The default value is false.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Gets or sets transition FPS [frames/sec] The default value is 25.

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

**Returns:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

Gets or sets transition FPS [frames/sec] The default value is 25.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Gets or sets default delay time [ms]. This value will be used if [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition#setAdvanceAfterTime-long-) is not set. The default value is 1000.

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

**Returns:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)

Obtient ou définit le délai par défaut [ms]. Cette valeur sera utilisée si [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) n'est pas défini. La valeur par défaut est 1000.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |