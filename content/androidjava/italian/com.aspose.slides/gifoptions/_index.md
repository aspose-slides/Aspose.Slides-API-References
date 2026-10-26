---
title: GifOptions
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta le opzioni di esportazione GIF.
type: docs
url: /it/com.aspose.slides/gifoptions/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Rappresenta le opzioni di esportazione GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // la dimensione della GIF risultante
>      gifOptions.setDefaultDelay(2000); // quanto tempo ogni diapositiva sarà mostrata prima di passare alla successiva
>      gifOptions.setTransitionFps(35); // aumenta gli FPS per una migliore qualità dell'animazione di transizione
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inizializza una nuova istanza della classe GifOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Ottiene o imposta la dimensione del fotogramma. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Ottiene o imposta la dimensione del fotogramma. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina se le diapositive nascoste saranno esportate. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina se le diapositive nascoste saranno esportate. |
| [getTransitionFps()](#getTransitionFps--) | Ottiene o imposta i FPS di transizione [fotogrammi/sec] Il valore predefinito è 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Ottiene o imposta i FPS di transizione [fotogrammi/sec] Il valore predefinito è 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Ottiene o imposta il tempo di ritardo predefinito [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Ottiene o imposta il tempo di ritardo predefinito [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inizializza una nuova istanza della classe GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


Ottiene o imposta la dimensione del fotogramma.

--------------------

Se la dimensione è vuota, il valore verrà preso da [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Restituisce:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
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
public final boolean getExportHiddenSlides()
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


**Restituisce:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```


Ottiene o imposta i FPS di transizione [fotogrammi/sec] Il valore predefinito è 25.

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
public final void setTransitionFps(int value)
```


Ottiene o imposta i FPS di transizione [fotogrammi/sec] Il valore predefinito è 25.

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
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```


Ottiene o imposta il tempo di ritardo predefinito [ms]. Questo valore verrà usato se [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) non è impostato. Il valore predefinito è 1000.

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
public final void setDefaultDelay(int value)
```


Ottiene o imposta il tempo di ritardo predefinito [ms]. Questo valore verrà usato se [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) non è impostato. Il valore predefinito è 1000.

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
| --- | --- | --- |
| value | int |  |