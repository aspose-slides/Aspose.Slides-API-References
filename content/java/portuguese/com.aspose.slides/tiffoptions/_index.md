---
title: TiffOptions
second_title: Referência da API Aspose.Slides para Java
description: Fornece opções que controlam como uma apresentação é salva no formato TIFF.
type: docs
url: /pt/com.aspose.slides/tiffoptions/
---
**Herança:** java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Fornece opções que controlam como uma apresentação é salva no formato TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Instancia um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Salvando a apresentação em documento TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Instancia um objeto Presentation que representa um arquivo Presentation
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Instancia a classe TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Definindo o tipo de compressão
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Tipos de Compressão
>      // Default - Especifica o esquema de compressão padrão (LZW).
>      // None - Especifica que não há compressão.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Depth depends on the compression type and cannot be set manually.
>      // Resolution unit  is always equal to 2 (dots per inch)
>      // Definindo DPI da imagem
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Definir Tamanho da Imagem
>      opts.setImageSize(new Dimension(1728, 1078));
>      // Salvar a apresentação em TIFF com o tamanho de imagem especificado
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Instancia um objeto Presentation que representa um arquivo Presentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat contém os seguintes valores (as could be seen from documentation):
>      //Format1bppIndexed; // 1 bits por pixel, indexado.
>      //Format4bppIndexed; // 4 bits por pixel, indexado.
>      //Format8bppIndexed; // 8 bits por pixel, indexado.
>      //Format24bppRgb; // 24 bits por pixel, RGB.
>      //Format32bppArgb; // 32 bits por pixel, ARGB.
> 
>      // Salvar a apresentação em TIFF com o tamanho de imagem especificado
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Construtor padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getImageSize()](#getImageSize--) | Especifica o tamanho de uma imagem TIFF gerada. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | Especifica o tamanho de uma imagem TIFF gerada. |
| [getDpiX()](#getDpiX--) | Especifica a resolução horizontal em pontos por polegada. |
| [setDpiX(long value)](#setDpiX-long-) | Especifica a resolução horizontal em pontos por polegada. |
| [getDpiY()](#getDpiY--) | Especifica a resolução vertical em pontos por polegada. |
| [setDpiY(long value)](#setDpiY-long-) | Especifica a resolução vertical em pontos por polegada. |
| [getCompressionType()](#getCompressionType--) | Especifica o tipo de compressão. |
| [setCompressionType(int value)](#setCompressionType-int-) | Especifica o tipo de compressão. |
| [getPixelFormat()](#getPixelFormat--) | Especifica o formato de pixel para as imagens geradas. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Especifica o formato de pixel para as imagens geradas. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

Construtor padrão.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retorna:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é false.

**Retorna:**
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

### getImageSize() {#getImageSize--}
```
public final Dimension getImageSize()
```

Especifica o tamanho de uma imagem TIFF gerada. O valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no tamanho dos slides da apresentação. Leitura/gravação java.awt.Dimension.

**Retorna:**
java.awt.Dimension
### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public final void setImageSize(Dimension value)
```

Especifica o tamanho de uma imagem TIFF gerada. O valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no tamanho dos slides da apresentação. Leitura/gravação java.awt.Dimension.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

Especifica a resolução horizontal em pontos por polegada. Leitura/gravação long.

**Retorna:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

Especifica a resolução horizontal em pontos por polegada. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

Especifica a resolução vertical em pontos por polegada. Leitura/gravação long.

**Retorna:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

Especifica a resolução vertical em pontos por polegada. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

Especifica o tipo de compressão. Leitura/gravação [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Retorna:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

Especifica o tipo de compressão. Leitura/gravação [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

Especifica o formato de pixel para as imagens geradas. Leitura/gravação [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Retorna:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

Especifica o formato de pixel para as imagens geradas. Leitura/gravação [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final int getBwConversionMode()
```

Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada apenas se o CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) estiver definido como [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ou [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Leitura/gravação [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). O padrão é [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public final void setBwConversionMode(int value)
```

Especifica o algoritmo para converter uma imagem colorida em uma imagem em preto e branco. Esta opção será aplicada apenas se o CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) estiver definido como [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) ou [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3). Leitura/gravação [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). O padrão é [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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