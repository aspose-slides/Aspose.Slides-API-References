---
title: IGifOptions
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta le opzioni di esportazione GIF.
type: docs
url: /it/com.aspose.slides/igifoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Rappresenta le opzioni di esportazione GIF.
## Metodi

| Method | Description |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Ottiene o imposta la dimensione del fotogramma. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Ottiene o imposta la dimensione del fotogramma. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina se le diapositive nascoste saranno esportate. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina se le diapositive nascoste saranno esportate. |
| [getTransitionFps()](#getTransitionFps--) | Ottiene o imposta i FPS di transizione [frames/sec] Il valore predefinito è 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Ottiene o imposta i FPS di transizione [frames/sec] Il valore predefinito è 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Ottiene o imposta il tempo di ritardo predefinito [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Ottiene o imposta il tempo di ritardo predefinito [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```


Ottiene o imposta la dimensione del fotogramma.

--------------------

Se la dimensione è vuota, il valore verrà preso da [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Returns:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```


Ottiene o imposta la dimensione del fotogramma.

--------------------

Se la dimensione è vuota, il valore verrà preso da [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.

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


Determina se le diapositive nascoste saranno esportate. Il valore predefinito è false.

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


Ottiene o imposta i FPS di transizione [frames/sec] Il valore predefinito è 25.

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


Ottiene o imposta i FPS di transizione [frames/sec] Il valore predefinito è 25.

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

**Returns:**
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |