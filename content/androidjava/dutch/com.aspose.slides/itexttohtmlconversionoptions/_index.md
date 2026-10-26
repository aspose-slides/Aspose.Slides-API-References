---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Opties voor het extraheren van HTML uit de Pptx-tekst.
type: docs
url: /nl/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Opties voor het extraheren van HTML uit de Pptx-tekst.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Geeft een waarde terug of stelt deze in, waarmee wordt aangegeven of Clipboard-koppen moeten worden toegevoegd. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Geeft een waarde terug of stelt deze in, waarmee wordt aangegeven of Clipboard-koppen moeten worden toegevoegd. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Geeft een erfdiepte terug of stelt deze in voor texteigenschappen. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Geeft een erfdiepte terug of stelt deze in voor texteigenschappen. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Geeft een callback-object terug of stelt dit in, dat bepaalt hoe een extern object wordt opgeslagen. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Geeft een callback-object terug of stelt dit in, dat bepaalt hoe een extern object wordt opgeslagen. |
| [getEncodingName()](#getEncodingName--) | Geeft de naam van de HTML-codering terug of stelt deze in. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Geeft de naam van de HTML-codering terug of stelt deze in. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Geeft een waarde terug of stelt deze in, waarmee wordt aangegeven of Clipboard-koppen moeten worden toegevoegd. Read/write boolean.

**Retour:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Geeft een waarde terug of stelt deze in, waarmee wordt aangegeven of Clipboard-koppen moeten worden toegevoegd. Read/write boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Geeft een erfdiepte terug of stelt deze in voor texteigenschappen. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Retour:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Geeft een erfdiepte terug of stelt deze in voor texteigenschappen. Read/write [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Geeft een callback-object terug of stelt dit in, dat bepaalt hoe een extern object wordt opgeslagen. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Retour:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Geeft een callback-object terug of stelt dit in, dat bepaalt hoe een extern object wordt opgeslagen. Read/write [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Geeft de naam van de HTML-codering terug of stelt deze in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om ervoor te zorgen dat het bestand met deze codering wordt weggeschreven. Read/write String.

**Retour:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Geeft de naam van de HTML-codering terug of stelt deze in. Deze waarde wordt opgeslagen in het gegenereerde HTML-bestand, maar het is aan de aanroeper om ervoor te zorgen dat het bestand met deze codering wordt weggeschreven. Read/write String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |