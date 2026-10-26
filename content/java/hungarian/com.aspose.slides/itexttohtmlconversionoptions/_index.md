---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: A Pptx szöveg HTML-re történő kivonásának beállításai.
type: docs
url: /hu/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

A Pptx szöveg HTML-re történő kivonásának beállításai.
## Módszerek

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Értéket ad vissza vagy állít be, amely jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Értéket ad vissza vagy állít be, amely jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Értéket ad vissza vagy állít be a szöveg tulajdonságok öröklődési mélységét. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Értéket ad vissza vagy állít be a szöveg tulajdonságok öröklődési mélységét. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Értéket ad vissza vagy állít be egy visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Értéket ad vissza vagy állít be egy visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. |
| [getEncodingName()](#getEncodingName--) | Értéket ad vissza vagy állít be a HTML kódolás nevét. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Értéket ad vissza vagy állít be a HTML kódolás nevét. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Értéket ad vissza vagy állít be, amely jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Értéket ad vissza vagy állít be, amely jelzi, hogy a Vágólap fejlécek hozzá legyenek adva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Értéket ad vissza vagy állít be a szöveg tulajdonságok öröklődési mélységét. Olvasás/írás [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Visszatérési érték:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Értéket ad vissza vagy állít be a szöveg tulajdonságok öröklődési mélységét. Olvasás/írás [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Értéket ad vissza vagy állít be egy visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. Olvasás/írás [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Visszatérési érték:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Értéket ad vissza vagy állít be egy visszahívási objektumot, amely szabályozza, hogyan lesz tárolva a külső objektum. Olvasás/írás [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Értéket ad vissza vagy állít be a HTML kódolás nevét. Ez az érték a generált HTML fájlba lesz mentve, de a hívó felelőssége, hogy biztosítsa a fájl ezen a kódoláson való mentését. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Értéket ad vissza vagy állít be a HTML kódolás nevét. Ez az érték a generált HTML fájlba lesz mentve, de a hívó felelőssége, hogy biztosítsa a fájl ezen a kódoláson való mentését. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |