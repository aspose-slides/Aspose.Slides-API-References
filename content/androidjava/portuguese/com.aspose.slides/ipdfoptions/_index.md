---
title: IPdfOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam como uma apresentação é salva no formato Pdf.
type: docs
url: /pt/com.aspose.slides/ipdfoptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

Fornece opções que controlam como uma apresentação é salva em formato PDF.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. |
| [setTextCompression(int value)](#setTextCompression-int-) | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Verdadeiro para incorporar fontes TrueType para caracteres ASCII 32-127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Verdadeiro para incorporar fontes TrueType para caracteres ASCII 32-127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito. |
| [getJpegQuality()](#getJpegQuality--) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. |
| [getCompliance()](#getCompliance--) | Nível de conformidade desejado para o documento PDF gerado. |
| [setCompliance(int value)](#setCompliance-int-) | Nível de conformidade desejado para o documento PDF gerado. |
| [getPassword()](#getPassword--) | Definindo a senha do usuário para proteger o documento PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Definindo a senha do usuário para proteger o documento PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Verdadeiro para converter todos os metarquivos usados em uma apresentação para imagens PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Verdadeiro para converter todos os metarquivos usados em uma apresentação para imagens PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Verdadeiro para desenhar uma moldura preta ao redor de cada slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Verdadeiro para desenhar uma moldura preta ao redor de cada slide. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | Obtém ou define a cor transparente da imagem. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | Obtém ou define a cor transparente da imagem. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Aplica a cor transparente especificada a uma imagem se verdadeiro. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Aplica a cor transparente especificada a uma imagem se verdadeiro. |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. |
| [getIncludeOleData()](#getIncludeOleData--) | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. Leitura/gravação [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

O padrão é [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Retorna:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. Leitura/gravação [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

O padrão é [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como verdadeiro, para cada imagem na apresentação o algoritmo de compressão mais adequado será escolhido, o que levará a um tamanho menor do documento PDF resultante.

--------------------

A seleção da melhor taxa de compressão de imagem é computacionalmente custosa e consome uma quantidade adicional de RAM, e esta opção é falsa por padrão.

--------------------

O padrão é false.

**Retorna:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como verdadeiro, para cada imagem na apresentação o algoritmo de compressão mais adequado será escolhido, o que levará a um tamanho menor do documento PDF resultante.

--------------------

A seleção da melhor taxa de compressão de imagem é computacionalmente custosa e consome uma quantidade adicional de RAM, e esta opção é falsa por padrão.

--------------------

O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

Verdadeiro para incorporar fontes TrueType para caracteres ASCII 32-127. Fontes para códigos de caracteres maiores que 127 são sempre incorporadas. Leitura/gravação boolean.

--------------------

O padrão é **true**.

**Retorna:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

Verdadeiro para incorporar fontes TrueType para caracteres ASCII 32-127. Fontes para códigos de caracteres maiores que 127 são sempre incorporadas. Leitura/gravação boolean.

--------------------

O padrão é **true**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

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

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. Leitura/gravação String[].

**Retorna:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. Leitura/gravação String[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Retorna:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito. Esta abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Retorna:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito. Esta abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes. Leitura/gravação boolean.

--------------------

O padrão é **false**.

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

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF. O valor pode variar de 0 a 100, onde 0 significa a pior qualidade mas compressão máxima e 100 significa a melhor qualidade mas compressão mínima.

O valor padrão é **100**.

**Retorna:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leitura/gravação byte.

--------------------

Tem efeito somente quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvar no formato PDF. O valor pode variar de 0 a 100, onde 0 significa a pior qualidade mas compressão máxima e 100 significa a melhor qualidade mas compressão mínima.

O valor padrão é **100**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

Nível de conformidade desejado para o documento PDF gerado. Leitura/gravação [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

O padrão é [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Retorna:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

Nível de conformidade desejado para o documento PDF gerado. Leitura/gravação [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

O padrão é [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Definindo a senha do usuário para proteger o documento PDF. Leitura/gravação String.

**Retorna:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Definindo a senha do usuário para proteger o documento PDF. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retorna:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

Contém um conjunto de sinalizadores que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

Verdadeiro para converter todos os metarquivos usados em uma apresentação para imagens PNG. Leitura/gravação boolean.

--------------------

O padrão é **true**. Um documento PDF pode conter gráficos vetoriais e imagens raster. Se SaveMetafilesAsPng for definido como true, a imagem Metafile de origem será convertida para o formato PNG e salva no PDF como uma imagem raster. Se SaveMetafilesAsPng for definido como false, a Metafile de origem será convertida para gráficos vetoriais PDF. Cada abordagem tem vantagens e desvantagens. Por exemplo, se a Metafile for convertida para PNG, pode haver perda de qualidade durante a redimensionamento do documento resultante. Se a Metafile for convertida para gráficos vetoriais PDF, podem ocorrer problemas de desempenho na ferramenta de visualização de PDF.

**Retorna:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

Verdadeiro para converter todos os metarquivos usados em uma apresentação para imagens PNG. Leitura/gravação boolean.

--------------------

O padrão é **true**. Um documento PDF pode conter gráficos vetoriais e imagens raster. Se SaveMetafilesAsPng for definido como true, a imagem Metafile de origem será convertida para o formato PNG e salva no PDF como uma imagem raster. Se SaveMetafilesAsPng for definido como false, a Metafile de origem será convertida para gráficos vetoriais PDF. Cada abordagem tem vantagens e desvantagens. Por exemplo, se a Metafile for convertida para PNG, pode haver perda de qualidade durante a redimensionamento do documento resultante. Se a Metafile for convertida para gráficos vetoriais PDF, podem ocorrer problemas de desempenho na ferramenta de visualização de PDF.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. Leitura/gravação float.

Valor: O efeito deste parâmetro depende de alguns fatores. O algoritmo tenta obter o melhor tamanho de imagem de saída de acordo com o valor da propriedade, o tamanho da imagem de origem e o tamanho da moldura da imagem. O uso de valores de propriedade semelhantes pode dar o mesmo resultado. Recomenda-se usar passo 16 ou 32 para obter efeito visível.

--------------------

A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.

O valor padrão é **96**.

**Retorna:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. Leitura/gravação float.

Valor: O efeito deste parâmetro depende de alguns fatores. O algoritmo tenta obter o melhor tamanho de imagem de saída de acordo com o valor da propriedade, o tamanho da imagem de origem e o tamanho da moldura da imagem. O uso de valores de propriedade semelhantes pode dar o mesmo resultado. Recomenda-se usar passo 16 ou 32 para obter efeito visível.

--------------------

A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.

O valor padrão é **96**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

Verdadeiro para desenhar uma moldura preta ao redor de cada slide. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Retorna:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

Verdadeiro para desenhar uma moldura preta ao redor de cada slide. Leitura/gravação boolean.

--------------------

O padrão é **false**.

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
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
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
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Integer getImageTransparentColor()
```

Obtém ou define a cor transparente da imagem.

Valor: A cor transparente da imagem.

**Retorna:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

Obtém ou define a cor transparente da imagem.

Valor: A cor transparente da imagem.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

Aplica a cor transparente especificada a uma imagem se verdadeiro.

**Retorna:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

Aplica a cor transparente especificada a uma imagem se verdadeiro.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fornece opções que controlam a aparência dos objetos Ink no documento exportado. Somente leitura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retorna:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura/gravação boolean.

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

O padrão é  **false** .

**Retorna:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura/gravação boolean.

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

O padrão é  **false** .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |