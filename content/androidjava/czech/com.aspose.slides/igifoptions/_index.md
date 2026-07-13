---
title: IGifOptions
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje možnosti exportu GIF.
type: docs
url: /cs/com.aspose.slides/igifoptions/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Reprezentuje možnosti exportu GIF.

## Metody

| Metoda | Popis |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Získává nebo nastavuje velikost rámce. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Získává nebo nastavuje velikost rámce. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Určuje, zda budou skryté snímky exportovány. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Určuje, zda budou skryté snímky exportovány. |
| [getTransitionFps()](#getTransitionFps--) | Získává nebo nastavuje FPS přechodu [frames/sec]. Výchozí hodnota je 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Získává nebo nastavuje FPS přechodu [frames/sec]. Výchozí hodnota je 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Získává nebo nastavuje výchozí dobu zpoždění [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Získává nebo nastavuje výchozí dobu zpoždění [ms]. |

### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

Získává nebo nastavuje velikost rámce.

--------------------

Pokud je velikost prázdná, bude hodnota převzata z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Vrací:**
[Size](../../com.aspose.slides.android/size)

### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

Získává nebo nastavuje velikost rámce.

--------------------

Pokud je velikost prázdná, bude hodnota převzata z [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

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

Získává nebo nastavuje FPS přechodu [frames/sec]. Výchozí hodnota je 25.

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

Získává nebo nastavuje FPS přechodu [frames/sec]. Výchozí hodnota je 25.

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

Získává nebo nastavuje výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) není nastavena. Výchozí hodnota je 1000.

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

Získává nebo nastavuje výchozí dobu zpoždění [ms]. Tato hodnota bude použita, pokud [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) není nastavena. Výchozí hodnota je 1000.

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