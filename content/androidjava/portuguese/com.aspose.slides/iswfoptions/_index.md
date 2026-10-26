---
title: ISwfOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Fornece opções que controlam como uma apresentação é salva no formato SWF.
type: docs
url: /pt/com.aspose.slides/iswfoptions/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Fornece opções que controlam como uma apresentação é salva no formato SWF.
## Métodos

| Método | Descrição |
| --- | --- |
| [getCompressed()](#getCompressed--) | Especifica se o documento SWF gerado deve ser compactado ou não. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Especifica se o documento SWF gerado deve ser compactado ou não. |
| [getViewerIncluded()](#getViewerIncluded--) | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. |
| [getShowPageBorder()](#getShowPageBorder--) | Especifica se a borda ao redor das páginas deve ser mostrada. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Especifica se a borda ao redor das páginas deve ser mostrada. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica se o documento gerado deve incluir slides ocultos ou não. |
| [getShowFullScreen()](#getShowFullScreen--) | Mostrar/ocultar botão de tela cheia. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Mostrar/ocultar botão de tela cheia. |
| [getShowPageStepper()](#getShowPageStepper--) | Mostrar/ocultar seletor de página. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Mostrar/ocultar seletor de página. |
| [getShowSearch()](#getShowSearch--) | Mostrar/ocultar seção de pesquisa. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Mostrar/ocultar seção de pesquisa. |
| [getShowTopPane()](#getShowTopPane--) | Mostrar/ocultar todo o painel superior. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Mostrar/ocultar todo o painel superior. |
| [getShowBottomPane()](#getShowBottomPane--) | Mostrar/ocultar painel inferior. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Mostrar/ocultar painel inferior. |
| [getShowLeftPane()](#getShowLeftPane--) | Mostrar/ocultar painel esquerdo. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Mostrar/ocultar painel esquerdo. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Iniciar com o painel esquerdo aberto. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Iniciar com o painel esquerdo aberto. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Habilitar/desabilitar menu de contexto. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Habilitar/desabilitar menu de contexto. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Imagem que será exibida como logotipo no canto superior direito do visualizador. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Imagem que será exibida como logotipo no canto superior direito do visualizador. |
| [getLogoLink()](#getLogoLink--) | Obtém ou define o endereço completo de hiperlink para um logotipo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Obtém ou define o endereço completo de hiperlink para um logotipo. |
| [getJpegQuality()](#getJpegQuality--) | Especifica a qualidade das imagens JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Especifica a qualidade das imagens JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```


Especifica se o documento SWF gerado deve ser compactado ou não. O padrão é true.

**Retorna:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```


Especifica se o documento SWF gerado deve ser compactado ou não. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```


Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é true.

**Retorna:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```


Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```


Especifica se a borda ao redor das páginas deve ser mostrada. O padrão é true.

**Retorna:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```


Especifica se a borda ao redor das páginas deve ser mostrada. O padrão é true.

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

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```


Mostrar/ocultar botão de tela cheia. Pode ser substituído em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```


Mostrar/ocultar botão de tela cheia. Pode ser substituído em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```


Mostrar/ocultar seletor de página. Pode ser substituído em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```


Mostrar/ocultar seletor de página. Pode ser substituído em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```


Mostrar/ocultar seção de pesquisa. Pode ser substituído em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```


Mostrar/ocultar seção de pesquisa. Pode ser substituído em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```


Mostrar/ocultar todo o painel superior. Pode ser substituído em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```


Mostrar/ocultar todo o painel superior. Pode ser substituído em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```


Mostrar/ocultar painel inferior. Pode ser substituído em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```


Mostrar/ocultar painel inferior. Pode ser substituído em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```


Mostrar/ocultar painel esquerdo. Pode ser substituído em flashvars. O padrão é true.

**Retorna:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```


Mostrar/ocultar painel esquerdo. Pode ser substituído em flashvars. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```


Iniciar com o painel esquerdo aberto. Pode ser substituído em flashvars. O padrão é false.

**Retorna:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```


Iniciar com o painel esquerdo aberto. Pode ser substituído em flashvars. O padrão é false.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```


Habilitar/desabilitar menu de contexto. O padrão é true.

**Retorna:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```


Habilitar/desabilitar menu de contexto. O padrão é true.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```


Imagem que será exibida como logotipo no canto superior direito do visualizador. A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente.

**Retorna:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```


Imagem que será exibida como logotipo no canto superior direito do visualizador. A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```


Obtém ou define o endereço completo de hiperlink para um logotipo. Tem efeito somente se um (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) for especificado.

**Retorna:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```


Obtém ou define o endereço completo de hiperlink para um logotipo. Tem efeito somente se um (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) for especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


Especifica a qualidade das imagens JPEG. O padrão é 95.

**Retorna:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


Especifica a qualidade das imagens JPEG. O padrão é 95.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propriedade não suporta atribuição de objetos do tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Obtém ou define o modo como os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Esta propriedade não suporta atribuição de objetos do tipo [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
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