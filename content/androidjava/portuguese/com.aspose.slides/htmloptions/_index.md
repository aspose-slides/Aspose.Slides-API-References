---
title: HtmlOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa opções de exportação HTML.
type: docs
url: /pt/com.aspose.slides/htmloptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Representa opções de exportação HTML.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Cria um novo objeto HtmlOptions especificando o callback. |
| [HtmlOptions()](#HtmlOptions--) | Cria um novo objeto HtmlOptions para salvar em um único arquivo HTML. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Retorna ou define o modelo HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Retorna ou define o modelo HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Retorna ou define opções de formato de imagem de slide. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Retorna ou define opções de formato de imagem de slide. |
| [getJpegQuality()](#getJpegQuality--) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro de um documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro de um documento PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa o nível de compressão das imagens |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa o nível de compressão das imagens |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True para excluir os atributos width e height do contêiner svg – isso tornará o layout responsivo. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True para excluir os atributos width e height do contêiner svg – isso tornará o layout responsivo. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Cria um novo objeto HtmlOptions especificando o callback.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Objeto callback que controla a gravação do projeto. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Cria um novo objeto HtmlOptions para salvar em um único arquivo HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtém ou define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorno:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtém ou define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retorno:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Retorno:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Retorna ou define o modelo HTML. Leitura/gravação [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Retorno:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Retorna ou define o modelo HTML. Leitura/gravação [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

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
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorno:**
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
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Retorna ou define opções de formato de imagem de slide. Leitura/gravação [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Retorno:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Retorna ou define opções de formato de imagem de slide. Leitura/gravação [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Retorna ou define um valor que determina a qualidade das imagens JPEG dentro de um documento PDF. Leitura/gravação byte.

--------------------

Tem efeito apenas quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF. O valor pode variar de 0 a 100, onde 0 significa a pior qualidade mas compressão máxima e 100 significa a melhor qualidade mas compressão mínima.

O valor padrão é **95**.

**Retorno:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Retorna ou define um valor que determina a qualidade das imagens JPEG dentro de um documento PDF. Leitura/gravação byte.

--------------------

Tem efeito apenas quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF. O valor pode variar de 0 a 100, onde 0 significa a pior qualidade mas compressão máxima e 100 significa a melhor qualidade mas compressão mínima.

O valor padrão é **95**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Representa o nível de compressão das imagens

**Retorno:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Representa o nível de compressão das imagens

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se true, as partes recortadas serão removidas; se false, elas serão serializadas no documento (o que pode levar a um arquivo maior)

**Retorno:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se true, as partes recortadas serão removidas; se false, elas serão serializadas no documento (o que pode levar a um arquivo maior)

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True para excluir os atributos width e height do contêiner svg – isso tornará o layout responsivo. False – caso contrário. Leitura/gravação boolean.

**Retorno:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True para excluir os atributos width e height do contêiner svg – isso tornará o layout responsivo. False – caso contrário. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |