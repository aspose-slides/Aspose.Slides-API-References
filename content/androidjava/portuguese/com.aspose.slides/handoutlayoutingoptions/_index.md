---
title: HandoutLayoutingOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa o modo de layout da apresentação de folhetos para exportação.
type: docs
url: /pt/com.aspose.slides/handoutlayoutingoptions/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

Representa o modo de layout da apresentação de folhetos para exportação.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | Inicializa os valores padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getHandout()](#getHandout--) | Especifica quantos slides e em que sequência serão colocados na página [HandoutType](../../com.aspose.slides/handouttype). |
| [setHandout(int value)](#setHandout-int-) | Especifica quantos slides e em que sequência serão colocados na página [HandoutType](../../com.aspose.slides/handouttype). |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | Especifica se deve ou não imprimir os números dos slides exibidos. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | Especifica se deve ou não imprimir os números dos slides exibidos. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | Especifica se deve desenhar quadros ao redor dos slides exibidos ou não. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | Especifica se deve desenhar quadros ao redor dos slides exibidos ou não. |
| [getPrintComments()](#getPrintComments--) | Especifica se deve ou não exibir comentários nos slides |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | Especifica se deve ou não exibir comentários nos slides |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```


Inicializa os valores padrão.

### getHandout() {#getHandout--}
```
public final int getHandout()
```


Especifica quantos slides e em que sequência serão colocados na página [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **HandoutType.Handouts6Horizontal** .

**Retorna:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```


Especifica quantos slides e em que sequência serão colocados na página [HandoutType](../../com.aspose.slides/handouttype).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **HandoutType.Handouts6Horizontal** .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```


Especifica se deve ou não imprimir os números dos slides exibidos.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **true** .

**Retorna:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```


Especifica se deve ou não imprimir os números dos slides exibidos.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **true** .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```


Especifica se deve desenhar quadros ao redor dos slides exibidos ou não.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **true** .

**Retorna:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```


Especifica se deve desenhar quadros ao redor dos slides exibidos ou não.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **true** .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```


Especifica se deve ou não exibir comentários nos slides

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **false** .

**Retorna:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```


Especifica se deve ou não exibir comentários nos slides

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new com.aspose.slides.android.Size(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

O valor padrão é  **false** .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |