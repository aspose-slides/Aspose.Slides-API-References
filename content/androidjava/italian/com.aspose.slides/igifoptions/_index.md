---
title: IGifOptions
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le opzioni di esportazione GIF.
type: docs
url: /it/com.aspose.slides/igifoptions/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Rappresenta le opzioni di esportazione GIF.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Ottiene o imposta la dimensione del fotogramma. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Ottiene o imposta la dimensione del fotogramma. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina se le diapositive nascoste verranno esportate. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina se le diapositive nascoste verranno esportate. |
| [getTransitionFps()](#getTransitionFps--) | Ottiene o imposta i FPS di transizione [frames/sec]. Il valore predefinito è 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Ottiene o imposta i FPS di transizione [frames/sec]. Il valore predefinito è 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Ottiene o imposta il tempo di ritardo predefinito [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Ottiene o imposta il tempo di ritardo predefinito [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```

Ottiene o imposta la dimensione del fotogramma.

--------------------

Se la dimensione è vuota, il valore verrà preso da [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Restituisce:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```

Ottiene o imposta la dimensione del fotogramma.

--------------------

Se la dimensione è vuota, il valore verrà preso da [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```

Determina se le diapositive nascoste verranno esportate. Il valore predefinito è false.

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

**Restituisce:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```

Determina se le diapositive nascoste verranno esportate. Il valore predefinito è false.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | |
| value | boolean |  |
### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```

Ottiene o imposta i FPS di transizione [frames/sec]. Il valore predefinito è 25.

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

**Restituisce:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```

Ottiene o imposta i FPS di transizione [frames/sec]. Il valore predefinito è 25.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | |
| value | int |  |
### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```

Ottiene o imposta il tempo di ritardo predefinito [ms]. Questo valore sarà usato se [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) non è impostato. Il valore predefinito è 1000.

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

**Restituisce:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```

Ottiene o imposta il tempo di ritardo predefinito [ms]. Questo valore sarà usato se [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) non è impostato. Il valore predefinito è 1000.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | |
| value | int |  |