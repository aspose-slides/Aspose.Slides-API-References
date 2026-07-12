---
title: IHtmlOptions
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa opções de exportação HTML.
type: docs
url: /pt/com.aspose.slides/ihtmloptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Representa opções de exportação HTML.
## Métodos

| Método | Descrição |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Retorna ou define o modelo HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Retorna ou define o modelo HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Retorna ou define opções de formato de imagem de slide. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Retorna ou define opções de formato de imagem de slide. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getJpegQuality()](#getJpegQuality--) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa o nível de compressão das imagens Leitura/gravação [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa o nível de compressão das imagens Leitura/gravação [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Verdadeiro para excluir os atributos de largura e altura do contêiner SVG - isso tornará o layout responsivo. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Verdadeiro para excluir os atributos de largura e altura do contêiner SVG - isso tornará o layout responsivo. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Retorna ou define o modelo HTML. Leitura/gravação [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Retorna:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Retorna ou define o modelo HTML. Leitura/gravação [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Retorna ou define opções de formato de imagem de slide. Leitura/gravação [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Retorna:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Retorna ou define opções de formato de imagem de slide. Leitura/gravação [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é falso.

**Retorna:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é falso.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leitura/gravação byte.

--------------------

Tem efeito somente quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF. O valor pode variar de 0 a 100, onde 0 significa pior qualidade, mas compressão máxima, e 100 significa melhor qualidade, mas compressão mínima.

O valor padrão é **95**.

**Retorna:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leitura/gravação byte.

--------------------

Tem efeito somente quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF. O valor pode variar de 0 a 100, onde 0 significa pior qualidade, mas compressão máxima, e 100 significa melhor qualidade, mas compressão mínima.

O valor padrão é **95**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Representa o nível de compressão das imagens Leitura/gravação [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Retorna:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Representa o nível de compressão das imagens Leitura/gravação [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas; se falso, serão serializadas no documento (o que pode levar a um arquivo maior) Leitura/gravação boolean.

**Retorna:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas; se falso, serão serializadas no documento (o que pode levar a um arquivo maior) Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

Verdadeiro para excluir os atributos de largura e altura do contêiner SVG - isso tornará o layout responsivo. Falso - caso contrário. Leitura/gravação boolean.

**Retorna:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

Verdadeiro para excluir os atributos de largura e altura do contêiner SVG - isso tornará o layout responsivo. Falso - caso contrário. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como verdadeiro, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como falso.

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


**Retorna:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Obtém ou define um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como verdadeiro, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade é definida como falso.

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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Retorna:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract IInkOptions getInkOptions()
```

Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retorna:**
[IInkOptions](../../com.aspose.slides/iinkoptions)