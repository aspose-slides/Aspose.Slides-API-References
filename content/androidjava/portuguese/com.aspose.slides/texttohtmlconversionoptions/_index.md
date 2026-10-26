---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides para Android via Referência da API Java
description: Opções para extrair HTML do texto Pptx.
type: docs
url: /pt/com.aspose.slides/texttohtmlconversionoptions/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Opções para extrair HTML do texto Pptx.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Obtém ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Obtém ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Obtém ou define a profundidade de herança para propriedades de texto. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Obtém ou define a profundidade de herança para propriedades de texto. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Obtém ou define um objeto de retorno de chamada que controla como o objeto externo será armazenado. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Obtém ou define um objeto de retorno de chamada que controla como o objeto externo será armazenado. |
| [getEncodingName()](#getEncodingName--) | Obtém ou define o nome da codificação html. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Obtém ou define o nome da codificação html. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Obtém ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. Leitura/gravação booleano.

**Retorna:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Obtém ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. Leitura/gravação booleano.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Obtém ou define a profundidade de herança para propriedades de texto. Leitura/gravação [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Retorna:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Obtém ou define a profundidade de herança para propriedades de texto. Leitura/gravação [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Obtém ou define um objeto de retorno de chamada que controla como o objeto externo será armazenado. Leitura/gravação [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Retorna:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Obtém ou define um objeto de retorno de chamada que controla como o objeto externo será armazenado. Leitura/gravação [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Obtém ou define o nome da codificação html. Este valor será salvo no arquivo HTML gerado, mas cabe ao chamador garantir que o arquivo seja salvo nesta codificação. Leitura/gravação String.

**Retorna:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Obtém ou define o nome da codificação html. Este valor será salvo no arquivo HTML gerado, mas cabe ao chamador garantir que o arquivo seja salvo nesta codificação. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |