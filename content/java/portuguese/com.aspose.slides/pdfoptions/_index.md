---
title: PdfOptions
second_title: Referência da API Aspose.Slides para Java
description: Fornece opções que controlam como uma apresentação é salva no formato Pdf.
type: docs
url: /pt/com.aspose.slides/pdfoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

Fornece opções que controlam como uma apresentação é salva no formato Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancia a classe PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Define a qualidade do JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // Define o comportamento para metarquivos
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Define o nível de compressão de texto
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Define o padrão PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Salva a apresentação como PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instancia uma classe Presentation que representa um arquivo PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancia a classe PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Adiciona slides ocultos
>      pdfOptions.setShowHiddenSlides(true);
>      // Salva a apresentação como PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instancia um objeto Presentation que representa um arquivo PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instancia a classe PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // Define a senha do PDF e as permissões de acesso
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Salva a apresentação como PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instancia um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Definindo o tipo e tamanho do slide
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Construtor padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fornece opções que controlam a aparência dos objetos Ink no documento exportado. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getTextCompression()](#getTextCompression--) | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. |
| [setTextCompression(int value)](#setTextCompression-int-) | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | Determina se Aspose.Slides incorporará fontes comuns para texto ASCII (faixa de códigos 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | Determina se Aspose.Slides incorporará fontes comuns para texto ASCII (faixa de códigos 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar comuns. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não oferece suporte a estilo negrito. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não oferece suporte a estilo negrito. |
| [getJpegQuality()](#getJpegQuality--) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. |
| [getCompliance()](#getCompliance--) | Nível de conformidade desejado para o documento PDF gerado. |
| [setCompliance(int value)](#setCompliance-int-) | Nível de conformidade desejado para o documento PDF gerado. |
| [getPassword()](#getPassword--) | Definindo a senha de usuário para proteger o documento PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Definindo a senha de usuário para proteger o documento PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | Verdadeiro para converter todos os metafiles usados em uma apresentação para imagens PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | Verdadeiro para converter todos os metafiles usados em uma apresentação para imagens PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | Verdadeiro para desenhar uma moldura preta ao redor de cada slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | Verdadeiro para desenhar uma moldura preta ao redor de cada slide. |
| [getImageTransparentColor()](#getImageTransparentColor--) | Obtém ou define a cor transparente da imagem. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | Obtém ou define a cor transparente da imagem. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | Aplica a cor transparente especificada a uma imagem se verdadeiro. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | Aplica a cor transparente especificada a uma imagem se verdadeiro. |
| [getIncludeOleData()](#getIncludeOleData--) | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

Construtor padrão.

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. Leitura/Gravação [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

O padrão é [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Retorna:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. Leitura/Gravação [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------
O padrão é [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como true, para cada imagem na apresentação o algoritmo de compressão mais adequado será escolhido, o que levará ao tamanho menor do documento PDF resultante.

--------------------

A seleção da proporção de compressão de imagem mais alta é computacionalmente cara e consome uma quantidade adicional de RAM, e esta opção é false por padrão.

--------------------

O padrão é false.

**Retorno:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como true, para cada imagem na apresentação o algoritmo de compressão mais adequado será escolhido, o que levará ao tamanho menor do documento PDF resultante.

--------------------

A seleção da proporção de compressão de imagem mais alta é computacionalmente cara e consome uma quantidade adicional de RAM, e esta opção é false por padrão.

--------------------

O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

Determina se Aspose.Slides incorporará fontes comuns para texto ASCII (faixa de códigos 33..127). Fontes para códigos de caracteres maiores que 127 são sempre incorporadas. A lista de fontes comuns inclui as 14 fontes base do PDF e fontes adicionais especificadas pelo usuário. Leitura/gravação boolean.

--------------------

O padrão é **true**.

**Retorno:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

Determina se Aspose.Slides incorporará fontes comuns para texto ASCII (faixa de códigos 33..127). Fontes para códigos de caracteres maiores que 127 são sempre incorporadas. A lista de fontes comuns inclui as 14 fontes base do PDF e fontes adicionais especificadas pelo usuário. Leitura/gravação boolean.

--------------------

O padrão é **true**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar como comuns. Leitura/gravação String[].

**Retorno:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

Retorna ou define um array de nomes de famílias de fontes definidos pelo usuário que o Aspose.Slides deve considerar como comuns. Leitura/gravação String[].

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

Determina se todos os caracteres da fonte devem ser incorporados ou apenas o subconjunto usado. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Retorno:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

Determina se todos os caracteres da fonte devem ser incorporados ou apenas o subconjunto usado. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo em negrito. Essa abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Retorno:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo em negrito. Essa abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes. Leitura/gravação boolean.

--------------------

O padrão é **false**.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leitura/gravação byte.

--------------------

Tem efeito apenas quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvá-lo no formato PDF. O valor pode variar de 0 a 100, onde 0 significa a pior qualidade, mas compressão máxima, e 100 significa a melhor qualidade, mas compressão mínima.

O valor padrão é **100**.

**Retorna:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Retorna ou define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leitura/gravação byte.

--------------------

Tem efeito apenas quando um documento contém imagens JPEG.

Use esta propriedade para obter ou definir a qualidade das imagens dentro de um documento ao salvá-lo no formato PDF. O valor pode variar de 0 a 100, onde 0 significa a pior qualidade, mas compressão máxima, e 100 significa a melhor qualidade, mas compressão mínima.

O valor padrão é **100**.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

Nível de conformidade desejado para o documento PDF gerado. Leitura/gravação [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

O padrão é [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Retorna:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

Nível de conformidade desejado para o documento PDF gerado. Leitura/gravação [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

O padrão é [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Definindo a senha do usuário para proteger o documento PDF. Leitura/gravação String.

**Retorna:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Definindo a senha do usuário para proteger o documento PDF. Leitura/gravação String.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public final void setAccessPermissions(int value)
```

Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

Verdadeiro para converter todos os metafiles usados em uma apresentação para imagens PNG. Leitura/gravação boolean.

--------------------

O valor padrão é **true**. O documento PDF pode conter gráficos vetoriais e imagens raster. Se SaveMetafilesAsPng estiver definido como true, então a imagem Metafile de origem é convertida para o formato Png e salva no Pdf como uma imagem raster. Se SaveMetafilesAsPng for definido como false, então o Metafile de origem é convertido para gráficos vetoriais do Pdf. Cada abordagem tem vantagens e desvantagens. Por exemplo, se o Metafile for convertido para PNG, pode haver perda de qualidade durante o dimensionamento do documento resultante. Se o Metafile for convertido para gráficos vetoriais do Pdf, podem ocorrer problemas de desempenho na ferramenta de visualização do Pdf.

**Retorna:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

Verdadeiro para converter todos os metafiles usados em uma apresentação para imagens PNG. Leitura/gravação boolean.

--------------------

O valor padrão é **true**. O documento PDF pode conter gráficos vetoriais e imagens raster. Se SaveMetafilesAsPng estiver definido como true, então a imagem Metafile de origem é convertida para o formato Png e salva no Pdf como uma imagem raster. Se SaveMetafilesAsPng for definido como false, então o Metafile de origem é convertido para gráficos vetoriais do Pdf. Cada abordagem tem vantagens e desvantagens. Por exemplo, se o Metafile for convertido para PNG, pode haver perda de qualidade durante o dimensionamento do documento resultante. Se o Metafile for convertido para gráficos vetoriais do Pdf, podem ocorrer problemas de desempenho na ferramenta de visualização do Pdf.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. Leitura/gravação float.

Valor: O efeito deste parâmetro depende de alguns fatores. O algoritmo tenta obter o melhor tamanho de imagem de saída de acordo com o valor da propriedade, o tamanho da imagem de origem e o tamanho da moldura da imagem. O uso de valores de propriedade semelhantes pode gerar o mesmo resultado. Recomenda-se usar passo 16 ou 32 para obter efeito visível.

--------------------

A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.

O valor padrão é **96**.

**Retorna:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

Retorna ou define um valor que determina a resolução das imagens dentro do documento PDF. Leitura/gravação float.

Valor: O efeito deste parâmetro depende de alguns fatores. O algoritmo tenta obter o melhor tamanho de imagem de saída de acordo com o valor da propriedade, o tamanho da imagem de origem e o tamanho da moldura da imagem. O uso de valores de propriedade semelhantes pode gerar o mesmo resultado. Recomenda-se usar passo 16 ou 32 para obter efeito visível.

--------------------

A propriedade afeta o tamanho do arquivo, o tempo de exportação e a qualidade da imagem.

O valor padrão é **96**.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

Verdadeiro para desenhar uma moldura preta ao redor de cada slide. Leitura/gravação boolean.

--------------------

O valor padrão é **false**.

**Retorna:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

Verdadeiro para desenhar uma moldura preta ao redor de cada slide. Leitura/gravação boolean.

--------------------

O valor padrão é **false**.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

Obtém ou define a cor transparente da imagem.

Valor: A cor da transparência da imagem.

**Retorna:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

Obtém ou define a cor transparente da imagem.

Valor: A cor da transparência da imagem.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

Aplica a cor transparente especificada a uma imagem se verdadeiro.

**Retorna:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

Aplica a cor transparente especificada a uma imagem se verdadeiro.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura/gravação boolean.

--------------------

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

--------------------

O valor padrão é **false**.

**Retorna:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leitura/gravação boolean.

--------------------

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

--------------------

O valor padrão é **false**.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |