---
title: ITiffOptions
second_title: Referência da API Aspose.Slides para Java
description: Fornece opções que controlam como uma apresentação é salva no formato TIFF.
type: docs
url: /pt/com.aspose.slides/itiffoptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Fornece opções que controlam como uma apresentação é salva no formato TIFF.
## Métodos

| Método | Descrição |
| --- | --- |
| [getImageSize()](#getImageSize--) | Especifica o tamanho de uma imagem TIFF gerada. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Especifica o tamanho de uma imagem TIFF gerada. |
| [getDpiX()](#getDpiX--) | Especifica a resolução horizontal em pontos por polegada. |
| [setDpiX(long value)](#setDpiX-long-) | Especifica a resolução horizontal em pontos por polegada. |
| [getDpiY()](#getDpiY--) | Especifica a resolução vertical em pontos por polegada. |
| [setDpiY(long value)](#setDpiY-long-) | Especifica a resolução vertical em pontos por polegada. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getCompressionType()](#getCompressionType--) | Especifica o tipo de compressão. |
| [setCompressionType(int value)](#setCompressionType-int-) | Especifica o tipo de compressão. |
| [getPixelFormat()](#getPixelFormat--) | Especifica o formato de pixel para as imagens geradas. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Especifica o formato de pixel para as imagens geradas. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência de objetos Ink no documento exportado. |
### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```


Especifica o tamanho de uma imagem TIFF gerada. O valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no valor do tamanho do slide da apresentação. Leitura/Gravação java.awt.Dimension.

**Retorna:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```


Especifica o tamanho de uma imagem TIFF gerada. O valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no valor do tamanho do slide da apresentação. Leitura/Gravação java.awt.Dimension.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```


Especifica a resolução horizontal em pontos por polegada. Leitura/Gravação long.

**Retorna:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```


Especifica a resolução horizontal em pontos por polegada. Leitura/Gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```


Especifica a resolução vertical em pontos por polegada. Leitura/Gravação long.

**Retorna:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```


Especifica a resolução vertical em pontos por polegada. Leitura/Gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Retorna:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```


Especifica o tipo de compressão. Leitura/Gravação [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Retorna:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```


Especifica o tipo de compressão. Leitura/Gravação [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```


Especifica o formato de pixel para as imagens geradas. Leitura/Gravação [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Retorna:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```


Especifica o formato de pixel para as imagens geradas. Leitura/Gravação [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
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


Obtém ou define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```


Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada somente se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) estiver definido como [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ou [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Leitura/Gravação [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). O padrão é [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retorna:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```


Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada somente se CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) estiver definido como [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ou [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Leitura/Gravação [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). O padrão é [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```


Fornece opções que controlam a aparência de objetos Ink no documento exportado. Somente leitura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retorna:**
[IInkOptions](../../com.aspose.slides/iinkoptions)