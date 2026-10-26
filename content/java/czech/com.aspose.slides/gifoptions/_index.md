---
title: GifOptions
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje možnosti exportu GIF.
type: docs
url: /cs/com.aspose.slides/gifoptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechny implementované rozhraní:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Reprezentuje možnosti exportu GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // velikost výsledného GIFu
>      gifOptions.setDefaultDelay(2000); // jak dlouho bude každý snímek zobrazen, než bude změněn na další
>      gifOptions.setTransitionFps(35); // zvýšení FPS pro lepší kvalitu animačního přechodu
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorzy

| Constructor | Description |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicializuje novou instanci třídy GifOptions. |
## Metody

| Method | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Získává nebo nastavuje velikost rámce. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Získává nebo nastavuje velikost rámce. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Určuje, zda budou skryté snímky exportovány. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Určuje, zda budou skryté snímky exportovány. |
| [getTransitionFps()](#getTransitionFps--) | Získává nebo nastavuje FPS přechodu [frames/sec] Výchozí hodnota je 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Získává nebo nastavuje FPS přechodu [frames/sec] Výchozí hodnota je 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Získává nebo nastavuje výchozí dobu zpoždění [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Získává nebo nastavuje výchozí dobu zpoždění [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inicializuje novou instanci třídy GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```


Získává nebo nastavuje velikost rámce.

--------------------

Pokud je velikost prázdná, hodnota bude převzata z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Vrací:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```


Získává nebo nastavuje velikost rámce.

--------------------

Pokud je velikost prázdná, hodnota bude převzata z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.

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


**Vrací:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```


Určuje, zda budou skryté snímky exportovány. Výchozí hodnota je false.

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

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```


Získává nebo nastavuje FPS přechodu [frames/sec] Výchozí hodnota je 25.

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


**Vrací:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


Získává nebo nastavuje FPS přechodu [frames/sec] Výchozí hodnota je 25.

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

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


Získává nebo nastavuje výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud není nastaveno [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). Výchozí hodnota je 1000.

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

**Vrací:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```


Získává nebo nastavuje výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud není nastaveno [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). Výchozí hodnota je 1000.

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

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |