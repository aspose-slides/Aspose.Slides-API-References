---
title: GifOptions
second_title: Aspose.Slides pour Android via référence API Java
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
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // la taille du GIF résultant
>      gifOptions.setDefaultDelay(2000); // durée pendant laquelle chaque diapositive sera affichée avant de passer à la suivante
>      gifOptions.setTransitionFps(35); // augmenter les FPS pour améliorer la qualité de l'animation de transition
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initializes a new instance of the GifOptions class. |
## Methods

| Method | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Gets or sets frame size. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Gets or sets frame size. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determines whether hidden slides will be exported. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determines whether hidden slides will be exported. |
| [getTransitionFps()](#getTransitionFps--) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Gets or sets default delay time [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Gets or sets default delay time [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Initializes a new instance of the GifOptions class.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Gets or sets frame size.

--------------------

If the size is empty then the value will be taken from [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Returns:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Gets or sets frame size.

--------------------

If the size is empty then the value will be taken from [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
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

**Returns:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
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
public final int getTransitionFps()
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
public final void setTransitionFps(int value)
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
public final int getDefaultDelay()
```

Gets or sets default delay time [ms]. This value will be used if [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) is not set. The default value is 1000.

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
public final void setDefaultDelay(int value)


Obtient ou définit le temps de retard par défaut [ms]. Cette valeur sera utilisée si [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) n'est pas définie. La valeur par défaut est 1000.

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