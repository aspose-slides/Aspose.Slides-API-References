---
title: IGifOptions
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje možnosti exportu GIF.
type: docs
url: /cs/com.aspose.slides/igifoptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Reprezentuje možnosti exportu GIF.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Získá nebo nastaví velikost rámce. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Získá nebo nastaví velikost rámce. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Určuje, zda budou skryté snímky exportovány. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Určuje, zda budou skryté snímky exportovány. |
| [getTransitionFps()](#getTransitionFps--) | Získá nebo nastaví FPS přechodu [frames/sec]. Výchozí hodnota je 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Získá nebo nastaví FPS přechodu [frames/sec]. Výchozí hodnota je 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Získá nebo nastaví výchozí dobu zpoždění [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Získá nebo nastaví výchozí dobu zpoždění [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```

Získá nebo nastaví velikost rámce.

--------------------

Pokud je velikost prázdná, bude hodnota převzata z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Vrací:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```

Získá nebo nastaví velikost rámce.

--------------------

Pokud je velikost prázdná, bude hodnota převzata z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Získá nebo nastaví FPS přechodu [frames/sec]. Výchozí hodnota je 25.

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
public abstract void setTransitionFps(int value)
```

Získá nebo nastaví FPS přechodu [frames/sec]. Výchozí hodnota je 25.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Získá nebo nastaví výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud není nastaveno [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). Výchozí hodnota je 1000.

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
public abstract void setDefaultDelay(int value)
```

Získá nebo nastaví výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud není nastaveno [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-). Výchozí hodnota je 1000.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |