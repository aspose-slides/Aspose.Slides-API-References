---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides Android számára a Java API hivatkozáson keresztül
description: Beállítások a Pptx szövegből történő HTML kinyeréshez.
type: docs
url: /hu/com.aspose.slides/texttohtmlconversionoptions/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

HTML kinyerése a Pptx szövegből.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Visszaadja vagy beállítja az értéket, amely azt jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Visszaadja vagy beállítja az értéket, amely azt jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Visszaadja vagy beállítja az öröklődő mélységet a szövegtulajdonságokhoz. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Visszaadja vagy beállítja az öröklődő mélységet a szövegtulajdonságokhoz. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Visszaadja vagy beállítja azt a visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Visszaadja vagy beállítja azt a visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. |
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


Visszaadja vagy beállítja az értéket, amely azt jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. Olvasási/írási bool.

**Visszatérési érték:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Visszaadja vagy beállítja az értéket, amely azt jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. Olvasási/írási bool.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Visszaadja vagy beállítja az öröklődő mélységet a szövegtulajdonságokhoz. Olvasási/írási [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Visszatérési érték:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Visszaadja vagy beállítja az öröklődő mélységet a szövegtulajdonságokhoz. Olvasási/írási [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Visszaadja vagy beállítja azt a visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. Olvasási/írási [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Visszatér:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Visszaadja vagy beállítja azt a visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. Olvasási/írási [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Visszaadja vagy beállítja a HTML kódolás nevét. Ez az érték a generált HTML fájlba lesz mentve, de a hívó felelőssége, hogy biztosítsa a fájl ilyen kódolásban történő mentését. Olvasási/írási String.

**Visszatérési érték:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Visszaadja vagy beállítja a HTML kódolás nevét. Ez az érték a generált HTML fájlba lesz mentve, de a hívó felelőssége, hogy biztosítsa a fájl ilyen kódolásban történő mentését. Olvasási/írási String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |