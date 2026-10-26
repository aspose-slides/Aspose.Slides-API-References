---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /cs/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Možnosti extrakce HTML z textu Pptx.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. |
| [getEncodingName()](#getEncodingName--) | Vrací nebo nastavuje název kódování HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Vrací nebo nastavuje název kódování HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. Čtení/zápis boolean.

**Vrací:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Vrací nebo nastavuje hodnotu, která určuje, zda mají být přidány záhlaví schránky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. Čtení/zápis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Vrací:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Vrací nebo nastavuje dědící hloubku pro textové vlastnosti. Čtení/zápis [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. Čtení/zápis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Vrací:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Vrací nebo nastavuje objekt zpětného volání, který řídí, jak bude externí objekt uložen. Čtení/zápis [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Vrací nebo nastavuje název kódování HTML. Tato hodnota bude uložena do vygenerovaného souboru HTML, ale je na volajícím, aby zajistil, že soubor bude uložen v tomto kódování. Čtení/zápis String.

**Vrací:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Vrací nebo nastavuje název kódování HTML. Tato hodnota bude uložena do vygenerovaného souboru HTML, ale je na volajícím, aby zajistil, že soubor bude uložen v tomto kódování. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |