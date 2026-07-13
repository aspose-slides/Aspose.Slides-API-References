---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides voor Android via Java API Referentie
description: Opties voor het extraheren van HTML uit de Pptx-tekst.
type: docs
url: /nl/com.aspose.slides/texttohtmlconversionoptions/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Opties voor het extraheren van HTML uit de Pptx-tekst.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Geeft waarde terug of stelt deze in, wat aangeeft of klembordkoppen moeten worden toegevoegd. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Geeft waarde terug of stelt deze in, wat aangeeft of klembordkoppen moeten worden toegevoegd. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Geeft de erfdiepte voor teksteigenschappen terug of stelt deze in. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Geeft de erfdiepte voor teksteigenschappen terug of stelt deze in. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Geeft een callback-object terug of stelt deze in, dat bepaalt hoe een extern object wordt opgeslagen. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Geeft een callback-object terug of stelt deze in, dat bepaalt hoe een extern object wordt opgeslagen. |
| [getEncodingName()](#getEncodingName--) | Geeft de HTML-coderingnaam terug of stelt deze in. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Geeft de HTML-coderingnaam terug of stelt deze in. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Geeft waarde terug of stelt deze in, wat aangeeft of klembordkoppen moeten worden toegevoegd. Lezen/Schrijven boolean.

**Retour:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Geeft waarde terug of stelt deze in, wat aangeeft of klembordkoppen moeten worden toegevoegd. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Geeft de erfdiepte voor teksteigenschappen terug of stelt deze in. Lezen/Schrijven [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Retour:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Geeft de erfdiepte voor teksteigenschappen terug of stelt deze in. Lezen/Schrijven [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Geeft een callback-object terug of stelt deze in, dat bepaalt hoe een extern object wordt opgeslagen. Lezen/Schrijven [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Retour:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Geeft een callback-object terug of stelt deze in, dat bepaalt hoe een extern object wordt opgeslagen. Lezen/Schrijven [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Geeft de HTML-coderingnaam terug of stelt deze in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om te zorgen dat het bestand in deze codering wordt opgeslagen. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Geeft de HTML-coderingnaam terug of stelt deze in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om te zorgen dat het bestand in deze codering wordt opgeslagen. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |