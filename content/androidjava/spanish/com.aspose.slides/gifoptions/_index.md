---
title: GifOptions
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa las opciones de exportación GIF.
type: docs
url: /es/com.aspose.slides/gifoptions/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Representa las opciones de exportación GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // el tamaño del GIF resultante
>      gifOptions.setDefaultDelay(2000); // cuánto tiempo se mostrará cada diapositiva hasta que se cambie a la siguiente
>      gifOptions.setTransitionFps(35); // aumenta los FPS para mejorar la calidad de la animación de transición
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicializa una nueva instancia de la clase GifOptions. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Obtiene o establece el tamaño del marco. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Obtiene o establece el tamaño del marco. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina si las diapositivas ocultas se exportarán. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina si las diapositivas ocultas se exportarán. |
| [getTransitionFps()](#getTransitionFps--) | Obtiene o establece FPS de transición [frames/sec] El valor predeterminado es 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Obtiene o establece FPS de transición [frames/sec] El valor predeterminado es 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Obtiene o establece el tiempo de retardo predeterminado [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Obtiene o establece el tiempo de retardo predeterminado [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```

Inicializa una nueva instancia de la clase GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```

Obtiene o establece el tamaño del marco.

--------------------

Si el tamaño está vacío, entonces el valor se tomará de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Devuelve:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
```

Obtiene o establece el tamaño del marco.

--------------------

Si el tamaño está vacío, entonces el valor se tomará de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```

Determina si las diapositivas ocultas se exportarán. El valor predeterminado es false.

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


**Devuelve:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public final void setExportHiddenSlides(boolean value)
```

Determina si las diapositivas ocultas se exportarán. El valor predeterminado es false.

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


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public final int getTransitionFps()
```

Obtiene o establece FPS de transición [frames/sec] El valor predeterminado es 25.

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


**Devuelve:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```

Obtiene o establece FPS de transición [frames/sec] El valor predeterminado es 25.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public final int getDefaultDelay()
```

Obtiene o establece el tiempo de retardo predeterminado [ms]. Este valor se usará si [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) no está establecido. El valor predeterminado es 1000.

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

**Devuelve:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public final void setDefaultDelay(int value)
```

Obtiene o establece el tiempo de retardo predeterminado [ms]. Este valor se usará si [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) no está establecido. El valor predeterminado es 1000.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |