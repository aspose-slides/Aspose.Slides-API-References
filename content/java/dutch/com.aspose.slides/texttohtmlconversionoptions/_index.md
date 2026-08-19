---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides voor Java API Referentie
description: Opties voor het extraheren van HTML uit de Pptx-tekst.
type: docs
url: /nl/com.aspose.slides/texttohtmlconversionoptions/
---
**Erfenis:**
java.lang.Object

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Opties voor het extraheren van HTML uit de Pptx-tekst.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Geeft een waarde terug of stelt deze in, die aangeeft of Clipboard-headers moeten worden toegevoegd. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Geeft een waarde terug of stelt deze in, die aangeeft of Clipboard-headers moeten worden toegevoegd. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Geeft een ereditie-diepte terug of stelt deze in voor teksteigenschappen. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Geeft een ereditie-diepte terug of stelt deze in voor teksteigenschappen. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Geeft een callback-object terug of stelt het in dat bepaalt hoe een extern object wordt opgeslagen. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Geeft een callback-object terug of stelt het in dat bepaalt hoe een extern object wordt opgeslagen. |
| [getEncodingName()](#getEncodingName--) | Geeft de naam van de HTML-codering terug of stelt deze in. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Geeft de naam van de HTML-codering terug of stelt deze in. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Geeft een waarde terug of stelt deze in, die aangeeft of Clipboard-headers moeten worden toegevoegd. Read/write boolean.

**Retour:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Geeft een waarde terug of stelt deze in, die aangeeft of Clipboard-headers moeten worden toegevoegd. Read/write boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Geeft een ereditie-diepte terug of stelt deze in voor teksteigenschappen. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Retour:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Geeft een ereditie-diepte terug of stelt deze in voor teksteigenschappen. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Geeft een callback-object terug of stelt het in dat bepaalt hoe een extern object wordt opgeslagen. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Retour:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Geeft een callback-object terug of stelt het in dat bepaalt hoe een extern object wordt opgeslagen. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Geeft de naam van de HTML-codering terug of stelt deze in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om ervoor te zorgen dat het bestand in deze codering wordt opgeslagen. Read/write String.

**Retour:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Geeft de naam van de HTML-codering terug of stelt deze in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om ervoor te zorgen dat het bestand in deze codering wordt opgeslagen. Read/write String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |