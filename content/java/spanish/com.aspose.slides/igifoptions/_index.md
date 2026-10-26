---
title: IGifOptions
second_title: Referencia de API de Aspose.Slides para Java
description: Representa opciones de exportación GIF.
type: docs
url: /es/com.aspose.slides/igifoptions/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Representa opciones de exportación GIF.
## Métodos

| Método | Descripción |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Obtiene o establece el tamaño del fotograma. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Obtiene o establece el tamaño del fotograma. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina si las diapositivas ocultas se exportarán. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina si las diapositivas ocultas se exportarán. |
| [getTransitionFps()](#getTransitionFps--) | Obtiene o establece los FPS de transición [frames/sec]. El valor predeterminado es 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Obtiene o establece los FPS de transición [frames/sec]. El valor predeterminado es 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Obtiene o establece el tiempo de retardo predeterminado [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Obtiene o establece el tiempo de retardo predeterminado [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Dimension getFrameSize()
```

Obtiene o establece el tamaño del fotograma.

--------------------

Si el tamaño está vacío, entonces el valor se tomará de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Devuelve:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public abstract void setFrameSize(Dimension value)
```

Obtiene o establece el tamaño del fotograma.

--------------------

Si el tamaño está vacío, entonces el valor se tomará de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.Dimension |  |
### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
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
public abstract void setExportHiddenSlides(boolean value)
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
public abstract int getTransitionFps()
```

Obtiene o establece los FPS de transición [frames/sec]. El valor predeterminado es 25.

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
public abstract void setTransitionFps(int value)
```

Obtiene o establece los FPS de transición [frames/sec]. El valor predeterminado es 25.

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
public abstract int getDefaultDelay()
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
public abstract void setDefaultDelay(int value)
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