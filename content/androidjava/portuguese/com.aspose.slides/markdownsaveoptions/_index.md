---
title: MarkdownSaveOptions
second_title: Aspose.Slides para Android via Referência de API Java
description: Representa opções que controlam como a apresentação deve ser salva em markdown.
type: docs
url: /pt/com.aspose.slides/markdownsaveoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

Representa opções que controlam como a apresentação deve ser salva em markdown.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | Construtor. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getExportType()](#getExportType--) | Especifica a especificação markdown para converter a apresentação. |
| [setExportType(int value)](#setExportType-int-) | Especifica a especificação markdown para converter a apresentação. |
| [getBasePath()](#getBasePath--) | Especifica o caminho base onde o documento com recursos será salvo. |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | Especifica o caminho base onde o documento com recursos será salvo. |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | Especifica o nome da pasta para salvar imagens. |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | Especifica o nome da pasta para salvar imagens. |
| [getNewLineType()](#getNewLineType--) | Especifica se o documento gerado deve ter novas linhas \\r(Macintosh) de \\n(Unix) ou \\r\\n(Windows). |
| [setNewLineType(int value)](#setNewLineType-int-) | Especifica se o documento gerado deve ter novas linhas \\r(Macintosh) de \\n(Unix) ou \\r\\n(Windows). |
| [getShowComments()](#getShowComments--) | Especifica se o documento gerado deve exibir comentários ou não. |
| [setShowComments(boolean value)](#setShowComments-boolean-) | Especifica se o documento gerado deve exibir comentários ou não. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getShowSlideNumber()](#getShowSlideNumber--) | Especifica se o documento gerado deve exibir o número de cada slide ou não. |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | Especifica se o documento gerado deve exibir o número de cada slide ou não. |
| [getFlavor()](#getFlavor--) | Especifica a especificação markdown para converter a apresentação. |
| [setFlavor(int value)](#setFlavor-int-) | Especifica a especificação markdown para converter a apresentação. |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Obtém ou define a string de formato usada para cabeçalhos de número de slide na saída Markdown. |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Obtém ou define a string de formato usada para cabeçalhos de número de slide na saída Markdown. |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown. |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown. |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | Se definido como true, remove linhas vazias ou contendo apenas espaços em branco da saída final de Markdown. |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | Se definido como true, remove linhas vazias ou contendo apenas espaços em branco da saída final de Markdown. |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Ocorre para cada imagem não SVG (bitmap ou metafile) durante a exportação para Markdown. |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Ocorre para cada imagem SVG durante a exportação para Markdown. |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Construtor.

### getExportType() {#getExportType--}
```
public final int getExportType()
```

Especifica a especificação markdown para converter a apresentação. O padrão é  TextOnly .

**Retorna:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

Especifica a especificação markdown para converter a apresentação. O padrão é  TextOnly .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

Especifica o caminho base onde o documento com recursos será salvo. O padrão é o diretório atual da aplicação.

**Retorna:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

Especifica o caminho base onde o documento com recursos será salvo. O padrão é o diretório atual da aplicação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

Especifica o nome da pasta para salvar imagens. O padrão é  Images .

**Retorna:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

Especifica o nome da pasta para salvar imagens. O padrão é  Images .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

Especifica se o documento gerado deve ter novas linhas \\r(Macintosh) de \\n(Unix) ou \\r\\n(Windows). O padrão é  Unix .

**Retorna:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

Especifica se o documento gerado deve ter novas linhas \\r(Macintosh) de \\n(Unix) ou \\r\\n(Windows). O padrão é  Unix .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

Especifica se o documento gerado deve exibir comentários ou não. O padrão é false.

**Retorna:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

Especifica se o documento gerado deve exibir comentários ou não. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

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

### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

Especifica se o documento gerado deve exibir o número de cada slide ou não. O padrão é false.

**Retorna:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

Especifica se o documento gerado deve exibir o número de cada slide ou não. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

Especifica a especificação markdown para converter a apresentação. O padrão é  Multi-markdown .

**Retorna:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

Especifica a especificação markdown para converter a apresentação. O padrão é  Multi-markdown .

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Obtém ou define a string de formato usada para cabeçalhos de número de slide na saída Markdown. O formato deve incluir o "\{0\}" que será substituído pelo índice do slide durante a exportação. Exemplo: "\# Slide \{0\}" produzirá "\# Slide 1", "\# Slide 2", etc.

**Retorna:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Obtém ou define a string de formato usada para cabeçalhos de número de slide na saída Markdown. O formato deve incluir o "\{0\}" que será substituído pelo índice do slide durante a exportação. Exemplo: "\# Slide \{0\}" produzirá "\# Slide 1", "\# Slide 2", etc.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown. Esta propriedade define se os espaços consecutivos são: - preservados como caracteres de espaço regulares, - alternados entre espaços regulares e entidades de espaço não separável (�), - ou totalmente substituídos (após o primeiro) por um espaço não separável para preservar o alinhamento visual na saída Markdown. O valor padrão é [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Retorna:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Especifica como os caracteres de espaço regular repetidos devem ser tratados durante a exportação para Markdown. Esta propriedade define se os espaços consecutivos são: - preservados como caracteres de espaço regulares, - alternados entre espaços regulares e entidades de espaço não separável (�), - ou totalmente substituídos (após o primeiro) por um espaço não separável para preservar o alinhamento visual na saída Markdown. O valor padrão é [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

Se definido como true, remove linhas vazias ou contendo apenas espaços em branco da saída final de Markdown. O padrão é false.

**Retorna:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

Se definido como true, remove linhas vazias ou contendo apenas espaços em branco da saída final de Markdown. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Ocorre para cada imagem não SVG (bitmap ou metafile) durante a exportação para Markdown. Permite personalizar como a imagem é salva e referenciada. Se não for tratada, a imagem é salva localmente com um link relativo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Evento de salvamento de imagem Markdown. |

### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Ocorre para cada imagem SVG durante a exportação para Markdown. Permite substituir o salvamento padrão e a geração de links. Se não for tratada, o SVG é salvo localmente com um link relativo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Evento de salvamento de SVG Markdown. |