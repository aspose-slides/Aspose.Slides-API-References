---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /hu/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Beállítások a Pptx szövegéből történő HTML kinyeréséhez.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Visszatér vagy beállítja az értéket, jelezve, hogy a Clipboard fejlécek hozzá legyenek adva. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Visszatér vagy beállítja az értéket, jelezve, hogy a Clipboard fejlécek hozzá legyenek adva. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Visszatér vagy beállítja a szövegtulajdonságok öröklődő mélységét. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Visszatér vagy beállítja a szövegtulajdonságok öröklődő mélységét. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Visszatér vagy beállít egy visszahívási objektumot, amely szabályozza, hogyan lesz a külső objektum tárolva. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Visszatér vagy beállít egy visszahívási objektumot, amely szabályozza, hogyan lesz a külső objektum tárolva. |
| [getEncodingName()](#getEncodingName--) | Visszatér vagy beállítja a HTML kódolás nevét. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Visszatér vagy beállítja a HTML kódolás nevét. |

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Visszatér vagy beállít egy értéket, jelezve, hogy a Clipboard fejlécek hozzá legyenek adva. Olvasás/írás boolean.

**Returns:**
boolean

### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Visszatér vagy beállít egy értéket, jelezve, hogy a Clipboard fejlécek hozzá legyenek adva. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Visszatér vagy beállítja a szövegtulajdonságok öröklődő mélységét. Olvasás/írás [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Returns:**
int

### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Visszatér vagy beállítja a szövegtulajdonságok öröklődő mélységét. Olvasás/írás [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Visszatér vagy beállít egy visszahívási objektumot, amely szabályozza, hogyan lesz a külső objektum tárolva. Olvasás/írás [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returns:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)

### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Visszatér vagy beállít egy visszahívási objektumot, amely szabályozza, hogyan lesz a külső objektum tárolva. Olvasás/írás [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Visszatér vagy beállítja a HTML kódolás nevét. Ez az érték a létrehozott HTML fájlba kerül mentésre, de a hívó feladata biztosítani, hogy a fájl ebben a kódolásban legyen mentve. Olvasás/írás String.

**Returns:**
java.lang.String

### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Visszatér vagy beállítja a HTML kódolás nevét. Ez az érték a létrehozott HTML fájlba kerül mentésre, de a hívó feladata biztosítani, hogy a fájl ebben a kódolásban legyen mentve. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |