---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Možnosti extrahování HTML z textu Pptx.
type: docs
url: /cs/com.aspose.slides/texttohtmlconversionoptions/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Možnosti extrahování HTML z textu Pptx.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. |
| [getEncodingName()](#getEncodingName--) | Vrací nebo nastavuje název HTML kódování. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Vrací nebo nastavuje název HTML kódování. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. Čtení/zápis boolean.

**Vrací:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. Čtení/zápis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Vrací:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. Čtení/zápis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. Čtení/zápis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Vrací:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. Čtení/zápis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Vrací nebo nastavuje název HTML kódování. Tato hodnota bude uložena do vygenerovaného souboru HTML, ale je na volajícím, aby zajistil, že soubor bude uložen v tomto kódování. Čtení/zápis String.

**Vrací:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Vrací nebo nastavuje název HTML kódování. Tato hodnota bude uložena do vygenerovaného souboru HTML, ale je na volajícím, aby zajistil, že soubor bude uložen v tomto kódování. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |