---
title: GifOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de exportação de GIF.
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

Representa opções de exportação de GIF.

--------------------

> ```
> The following example shows how to converting presentations to animated GIF using custom settings.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      GifOptions gifOptions = new GifOptions();
>      gifOptions.setFrameSize(new com.aspose.slides.android.Size(960, 720)); // o tamanho do GIF resultante
>      gifOptions.setDefaultDelay(2000); // quanto tempo cada slide será exibido até ser alterado para o próximo
>      gifOptions.setTransitionFps(35); // aumentar FPS para melhorar a qualidade da animação de transição
>      pres.save("pres.gif", SaveFormat.Gif, gifOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [GifOptions()](#GifOptions--) | Initializes a new instance of the GifOptions class. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getFrameSize()](#getFrameSize--) | Gets or sets frame size. |
| [setFrameSize(Size value)](#setFrameSize-com.aspose.slides.android.Size-) | Gets or sets frame size. |
| [getExportHiddenSlides()](#getExportHiddenSlides--) | Determines whether hidden slides will be exported. |
| [setExportHiddenSlides(boolean value)](#setExportHiddenSlides-boolean-) | Determines whether hidden slides will be exported. |
| [getTransitionFps()](#getTransitionFps--) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [setTransitionFps(int value)](#setTransitionFps-int-) | Gets or sets transition FPS [frames/sec] The default value is 25. |
| [getDefaultDelay()](#getDefaultDelay--) | Gets or sets default delay time [ms]. |
| [setDefaultDelay(int value)](#setDefaultDelay-int-) | Gets or sets default delay time [ms]. |
### GifOptions() {#GifOptions--}
```
public GifOptions()
```


Inicializa uma nova instância da classe GifOptions.

### getFrameSize() {#getFrameSize--}
```
public final Size getFrameSize()
```


Obtém ou define o tamanho do quadro.

--------------------

Se o tamanho estiver vazio, o valor será obtido de [IPresentation.getSlideSize](../../com.aspose.slides/ipresentation\#getSlideSize)

**Retorna:**
[Size](../../com.aspose.slides.android/size)
### setFrameSize(Size value) {#setFrameSize-com.aspose.slides.android.Size-}
```
public final void setFrameSize(Size value)
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


Obtém ou define o FPS de transição [frames/sec]. O valor padrão é 25.

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


Obtém ou define o FPS de transição [frames/sec]. O valor padrão é 25.

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