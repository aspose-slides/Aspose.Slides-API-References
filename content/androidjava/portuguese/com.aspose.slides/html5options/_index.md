---
title: Html5Options
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de exportação HTML5.
type: docs
url: /pt/com.aspose.slides/html5options/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

Representa opções de exportação HTML5.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [Html5Options()](#Html5Options--) | Construtor padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Retorna ou define a opção de animação de transições. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Retorna ou define a opção de animação de transições. |
| [getAnimateShapes()](#getAnimateShapes--) | Retorna ou define a opção de animação de formas. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Retorna ou define a opção de animação de formas. |
| [getEmbedImages()](#getEmbedImages--) | Retorna ou define a opção de incorporação de imagens. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Retorna ou define a opção de incorporação de imagens. |
| [getOutputPath()](#getOutputPath--) | Determina onde os recursos externos devem ser armazenados. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Determina onde os recursos externos devem ser armazenados. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

Construtor padrão.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

Retorna ou define a opção de animação de transições. Booleano de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

Retorna ou define a opção de animação de transições. Booleano de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

Retorna ou define a opção de animação de formas. Booleano de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

Retorna ou define a opção de animação de formas. Booleano de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

Retorna ou define a opção de incorporação de imagens. Booleano de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

Retorna ou define a opção de incorporação de imagens. Booleano de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

Determina onde os recursos externos devem ser armazenados. String de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```

Determina onde os recursos externos devem ser armazenados. String de leitura/gravação.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como true, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Desativar ligaduras na renderização de texto
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como true, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Desativar ligaduras na renderização de texto
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |