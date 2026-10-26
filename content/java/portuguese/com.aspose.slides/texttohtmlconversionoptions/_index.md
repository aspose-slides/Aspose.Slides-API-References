---
title: TextToHtmlConversionOptions
second_title: Referência da API Aspose.Slides para Java
description: Opções para extrair HTML do texto Pptx.
type: docs
url: /pt/com.aspose.slides/texttohtmlconversionoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Retorna ou define o valor, indicando se cabeçalhos da área de transferência devem ser adicionados. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Retorna ou define o valor, indicando se cabeçalhos da área de transferência devem ser adicionados. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Retorna ou define a profundidade de herança para propriedades de texto. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Retorna ou define a profundidade de herança para propriedades de texto. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. |
| [getEncodingName()](#getEncodingName--) | Retorna ou define o nome da codificação HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Retorna ou define o nome da codificação HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Retorna ou define o valor, indicando se cabeçalhos da área de transferência devem ser adicionados. Leitura/gravação boolean.

**Retorna:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Retorna ou define o valor, indicando se cabeçalhos da área de transferência devem ser adicionados. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Retorna ou define a profundidade de herança para propriedades de texto. Leitura/gravação [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Retorna:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Retorna ou define a profundidade de herança para propriedades de texto. Leitura/gravação [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. Leitura/gravação [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Retorna:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. Leitura/gravação [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Retorna ou define o nome da codificação HTML. Este valor será salvo no arquivo HTML gerado, mas cabe ao chamador garantir que o arquivo seja salvo nesta codificação. Leitura/gravação String.

**Retorna:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Retorna ou define o nome da codificação HTML. Este valor será salvo no arquivo HTML gerado, mas cabe ao chamador garantir que o arquivo seja salvo nesta codificação. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |