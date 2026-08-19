---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Opties voor het extraheren van HTML uit de Pptx-tekst.
type: docs
url: /nl/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opties voor het extraheren van HTML uit de Pptx-tekst.
## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Returns or sets value, indicating if Clipboard headers should be added. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Returns or sets value, indicating if Clipboard headers should be added. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Returns or sets inhering depth for text properties. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Returns or sets inhering depth for text properties. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Returns or sets a callback object which controlls how external object will be stored. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Returns or sets a callback object which controlls how external object will be stored. |
| [getEncodingName()](#getEncodingName--) | Returns or sets html encoding name. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Returns or sets html encoding name. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Retourneert of stelt een waarde in, die aangeeft of klembordkoppen moeten worden toegevoegd. Lezen/schrijven boolean.

**Retour:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Retourneert of stelt een waarde in, die aangeeft of klembordkoppen moeten worden toegevoegd. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Retourneert of stelt de diepte van overerving voor teksteigenschappen in. Lezen/schrijven [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Retour:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Retourneert of stelt de diepte van overerving voor teksteigenschappen in. Lezen/schrijven [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Retourneert of stelt een callback-object in dat bepaalt hoe een extern object wordt opgeslagen. Lezen/schrijven [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Retour:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Retourneert of stelt een callback-object in dat bepaalt hoe een extern object wordt opgeslagen. Lezen/schrijven [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Retourneert of stelt de naam van de HTML-codering in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om te zorgen dat het bestand in deze codering wordt opgeslagen. Lezen/schrijven String.

**Retour:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Retourneert of stelt de naam van de HTML-codering in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om te zorgen dat het bestand in deze codering wordt opgeslagen. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |