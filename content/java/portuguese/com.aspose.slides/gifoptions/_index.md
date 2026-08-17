---
title: GifOptions
second_title: Referência da API Aspose.Slides para Java
description: Representa as opções de exportação GIF.
type: docs
url: /pt/com.aspose.slides/gifoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGifOptions](../../com.aspose.slides/igifoptions)
```
public class GifOptions extends SaveOptions implements IGifOptions
```

Representa as opções de exportação GIF.

--------------------

> ```
> O exemplo a seguir mostra como converter apresentações para GIF animado usando configurações personalizadas.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new Dimension(960, 720)); // o tamanho do GIF resultante
>      gifOptions.setDefaultDelay(2000); // quanto tempo cada slide será exibido até ser trocado para o próximo
>      gifOptions.setTransitionFps(35); // aumentar FPS para melhorar a qualidade da animação de transição
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [GifOptions()](#GifOptions--) | Inicializa uma nova instância da classe GifOptions. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Obtém ou define o tamanho do quadro. |
| [setFrameSize(Dimension value)](#setFrameSize-java.awt.Dimension-) | Obtém ou define o tamanho do quadro. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determina se os slides ocultos serão exportados. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determina se os slides ocultos serão exportados. |
| [getTransitionFps()](#getTransitionFps--) | Obtém ou define o FPS da transição [frames/sec]. O valor padrão é 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Obtém ou define o FPS da transição [frames/sec]. O valor padrão é 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Obtém ou define o tempo de atraso padrão [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Obtém ou define o tempo de atraso padrão [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inicializa uma nova instância da classe GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Dimension getFrameSize()
```


Obtém ou define o tamanho do quadro.

--------------------

Se o tamanho estiver vazio, o valor será obtido de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Retorna:**
java.awt.Dimension
### setFrameSize(Dimension value) {#setFrameSize-java.awt.Dimension-}
```
public final void setFrameSize(Dimension value)
```


Obtém ou define o tamanho do quadro.

--------------------

Se o tamanho estiver vazio, o valor será obtido de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getExportHiddenSlides() {#getExportHiddenSlides--}
```
public final boolean getExportHiddenSlides()
```


Determina se os slides ocultos serão exportados. O valor padrão é false.

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
public final void setExportHiddenSlides(boolean value)
```


Determina se os slides ocultos serão exportados. O valor padrão é false.

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
public final int getTransitionFps()
```


Obtém ou define o FPS da transição [frames/sec]. O valor padrão é 25.

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

**Retorna:**
int
### setTransitionFps(int value) {#setTransitionFps-int-}
```
public final void setTransitionFps(int value)
```


Obtém ou define o FPS da transição [frames/sec]. O valor padrão é 25.

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
public final int getDefaultDelay()
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
public final void setDefaultDelay(int value)
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