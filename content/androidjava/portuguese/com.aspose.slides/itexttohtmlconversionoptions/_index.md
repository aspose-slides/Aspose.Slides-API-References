---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opções para extrair HTML do texto Pptx.
type: docs
url: /pt/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opções para extrair HTML do texto Pptx.
## Methods

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Retorna ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Retorna ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Retorna ou define a profundidade de herança para propriedades de texto. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Retorna ou define a profundidade de herança para propriedades de texto. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. |
| [getEncodingName()](#getEncodingName--) | Retorna ou define o nome da codificação HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Retorna ou define o nome da codificação HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


Retorna ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. Leitura/Gravação boolean.

**Retorna:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


Retorna ou define o valor, indicando se os cabeçalhos da área de transferência devem ser adicionados. Leitura/Gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


Retorna ou define a profundidade de herança para propriedades de texto. Leitura/Gravação [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Retorna:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


Retorna ou define a profundidade de herança para propriedades de texto. Leitura/Gravação [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. Leitura/Gravação [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Retorna:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


Retorna ou define um objeto de callback que controla como o objeto externo será armazenado. Leitura/Gravação [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


Retorna ou define o nome da codificação HTML. Esse valor será salvo no arquivo HTML gerado, mas cabe ao chamador garantir que o arquivo será salvo nesta codificação. Leitura/Gravação String.

**Retorna:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


Retorna ou define o nome da codificação HTML. Esse valor será salvo no arquivo HTML gerado, mas cabe ao chamador garantir que o arquivo será salvo nesta codificação. Leitura/Gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |