---
title: IGifOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de exportação de GIF.
type: docs
url: /pt/com.aspose.slides/igifoptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IGifOptions extends ISaveOptions
```

Representa opções de exportação de GIF.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Obtém ou define o tamanho do quadro. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Obtém ou define o tamanho do quadro. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina se os slides ocultos serão exportados. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina se os slides ocultos serão exportados. |
| [getTransitionFps()](#getTransitionFps--) | Obtém ou define FPS da transição [frames/seg] O valor padrão é 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Obtém ou define FPS da transição [frames/seg] O valor padrão é 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Obtém ou define o tempo de atraso padrão [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Obtém ou define o tempo de atraso padrão [ms]. |
### getFrameSize() {#getFrameSize--}
```
public abstract Size getFrameSize()
```


Obtém ou define o tamanho do quadro.

--------------------

Se o tamanho estiver vazio, o valor será obtido de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Retorna:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public abstract void setFrameSize(Size value)
```


Obtém ou define o tamanho do quadro.

--------------------

Se o tamanho estiver vazio, o valor será obtido de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public abstract boolean getExportHiddenSlides()
```


Determina se os slides ocultos serão exportados. O valor padrão é falso.

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


**Retorna:**
boolean
### setExportHiddenSlides(boolean value) {#setExportHiddenSlides-boolean-}
```
public abstract void setExportHiddenSlides(boolean value)
```


Determina se os slides ocultos serão exportados. O valor padrão é falso.

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


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTransitionFps() {#getTransitionFps--}
```
public abstract int getTransitionFps()
```


Obtém ou define FPS da transição [frames/seg] O valor padrão é 25.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setTransitionFps(60);
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retorna:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public abstract void setTransitionFps(int value)
```


Obtém ou define FPS da transição [frames/seg] O valor padrão é 25.

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


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDefaultDelay() {#getDefaultDelay--}
```
public abstract int getDefaultDelay()
```


Obtém ou define o tempo de atraso padrão [ms]. Este valor será usado se [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) não estiver definido. O valor padrão é 1000.

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


**Retorna:**
int
### setDefaultDelay(int value) {#setDefaultDelay-int-}
```
public abstract void setDefaultDelay(int value)
```


Obtém ou define o tempo de atraso padrão [ms]. Este valor será usado se [ISlideShowTransition.getAdvanceAfterTime](../../com.aspose.slides/islideshowtransition\#getAdvanceAfterTime)/[ISlideShowTransition.setAdvanceAfterTime(long)](../../com.aspose.slides/islideshowtransition\#setAdvanceAfterTime-long-) não estiver definido. O valor padrão é 1000.

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


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |