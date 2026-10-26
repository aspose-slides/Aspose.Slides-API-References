---
title: SwfOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam como uma apresentação é salva no formato Swf.
type: docs
url: /pt/com.aspose.slides/swfoptions/
---
**Herança:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Fornece opções que controlam como uma apresentação é salva no formato Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instanciar um objeto Presentation que representa um arquivo de apresentação
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Salvando a apresentação e as páginas de notas
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Construtor padrão. |
## Métodos

| Método | Descrição |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getCompressed()](#getCompressed--) | Especifica se o documento SWF gerado deve ser comprimido ou não. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Especifica se o documento SWF gerado deve ser comprimido ou não. |
| [getViewerIncluded()](#getViewerIncluded--) | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. |
| [getShowPageBorder()](#getShowPageBorder--) | Especifica se a borda ao redor das páginas deve ser mostrada. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Especifica se a borda ao redor das páginas deve ser mostrada. |
| [getShowFullScreen()](#getShowFullScreen--) | Mostrar/ocultar botão de tela cheia. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Mostrar/ocultar botão de tela cheia. |
| [getShowPageStepper()](#getShowPageStepper--) | Mostrar/ocultar passo de página. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Mostrar/ocultar passo de página. |
| [getShowSearch()](#getShowSearch--) | Mostrar/ocultar seção de pesquisa. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Mostrar/ocultar seção de pesquisa. |
| [getShowTopPane()](#getShowTopPane--) | Mostrar/ocultar todo o painel superior. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Mostrar/ocultar todo o painel superior. |
| [getShowBottomPane()](#getShowBottomPane--) | Mostrar/ocultar painel inferior. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Mostrar/ocultar painel inferior. |
| [getShowLeftPane()](#getShowLeftPane--) | Mostrar/ocultar painel esquerdo. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Mostrar/ocultar painel esquerdo. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Iniciar com painel esquerdo aberto. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Iniciar com painel esquerdo aberto. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Habilitar/desabilitar menu de contexto. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Habilitar/desabilitar menu de contexto. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Imagem que será exibida como logotipo no canto superior direito do visualizador. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Imagem que será exibida como logotipo no canto superior direito do visualizador. |
| [getLogoLink()](#getLogoLink--) | Obtém ou define o endereço de hiperlink completo para um logotipo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Obtém ou define o endereço de hiperlink completo para um logotipo. |
| [getJpegQuality()](#getJpegQuality--) | Especifica a qualidade das imagens JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Especifica a qualidade das imagens JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


Construtor padrão.

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

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


Especifica se o documento SWF gerado deve ser comprimido ou não. O padrão é true.

**Retorna:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


Especifica se o documento SWF gerado deve ser comprimido ou não. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é true.

**Retorna:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


Especifica se a borda ao redor das páginas deve ser mostrada. O padrão é true.

**Retorna:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


Especifica se a borda ao redor das páginas deve ser mostrada. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


Mostrar/ocultar botão de tela cheia. Pode ser sobrescrito em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


Mostrar/ocultar botão de tela cheia. Pode ser sobrescrito em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


Mostrar/ocultar passo de página. Pode ser sobrescrito em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


Mostrar/ocultar passo de página. Pode ser sobrescrito em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


Mostrar/ocultar seção de pesquisa. Pode ser sobrescrito em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


Mostrar/ocultar seção de pesquisa. Pode ser sobrescrito em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


Mostrar/ocultar todo o painel superior. Pode ser sobrescrito em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


Mostrar/ocultar todo o painel superior. Pode ser sobrescrito em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


Mostrar/ocultar painel inferior. Pode ser sobrescrito em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


Mostrar/ocultar painel inferior. Pode ser sobrescrito em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


Mostrar/ocultar painel esquerdo. Pode ser sobrescrito em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


Mostrar/ocultar painel esquerdo. Pode ser sobrescrito em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


Iniciar com painel esquerdo aberto. Pode ser sobrescrito em flashvars. O padrão é false.

**Retorna:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


Iniciar com painel esquerdo aberto. Pode ser sobrescrito em flashvars. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


Habilitar/desabilitar menu de contexto. O padrão é true.

**Retorna:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


Habilitar/desabilitar menu de contexto. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


Imagem que será exibida como logotipo no canto superior direito do visualizador. A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente.

**Retorna:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


Imagem que será exibida como logotipo no canto superior direito do visualizador. A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


Obtém ou define o endereço de hiperlink completo para um logotipo. Só tem efeito se um (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) for especificado.

**Retorna:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


Obtém ou define o endereço de hiperlink completo para um logotipo. Só tem efeito se um (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) for especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


Especifica a qualidade das imagens JPEG. O padrão é 95.

**Retorna:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


Especifica a qualidade das imagens JPEG. O padrão é 95.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propriedade não suporta atribuição de objetos do tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Exemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
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


Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propriedade não suporta atribuição de objetos do tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Exemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |