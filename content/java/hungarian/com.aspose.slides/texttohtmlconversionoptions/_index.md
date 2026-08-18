---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides Java API-referencia
description: Beállítások a Pptx szövegből HTML kinyeréséhez.
type: docs
url: /hu/com.aspose.slides/texttohtmlconversionoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Pptx szövegből HTML kinyerésének lehetőségei.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Visszaadja vagy beállítja az értéket, amely jelzi, hogy a vágólap-fejeket hozzá kell-e adni. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Visszaadja vagy beállítja az értéket, amely jelzi, hogy a vágólap-fejeket hozzá kell-e adni. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Visszaadja vagy beállítja a szövegtulajdonságok öröklődési mélységét. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Visszaadja vagy beállítja a szövegtulajdonságok öröklődési mélységét. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Visszaadja vagy beállítja a visszahívási objektumot, amely szabályozza, hogyan lesz külső objektum tárolva. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Visszaadja vagy beállítja a visszahívási objektumot, amely szabályozza, hogyan lesz külső objektum tárolva. |
| [getEncodingName()](#getEncodingName--) | Visszaadja vagy beállítja a HTML kódolás nevét. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Visszaadja vagy beállítja a HTML kódolás nevét. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Visszaadja vagy beállítja az értéket, amely jelzi, hogy a vágólap-fejeket hozzá kell-e adni. Olvasás/írás boolean.

**Visszatér:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Visszaadja vagy beállítja az értéket, amely jelzi, hogy a vágólap-fejeket hozzá kell-e adni. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Visszaadja vagy beállítja a szövegtulajdonságok öröklődési mélységét. Olvasás/írás [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Visszatér:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Visszaadja vagy beállítja a szövegtulajdonságok öröklődési mélységét. Olvasás/írás [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Visszaadja vagy beállítja a visszahívási objektumot, amely szabályozza, hogyan lesz külső objektum tárolva. Olvasás/írás [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Visszatér:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Visszaadja vagy beállítja a visszahívási objektumot, amely szabályozza, hogyan lesz külső objektum tárolva. Olvasás/írás [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Visszaadja vagy beállítja a HTML kódolás nevét. Ez az érték a létrehozott HTML fájlba lesz mentve, de a hívó feladata biztosítani, hogy a fájl ebben a kódolásban legyen mentve. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Visszaadja vagy beállítja a HTML kódolás nevét. Ez az érték a létrehozott HTML fájlba lesz mentve, de a hívó feladata biztosítani, hogy a fájl ebben a kódolásban legyen mentve. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |