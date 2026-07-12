---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Optionen zum Extrahieren von HTML aus dem Pptx-Text.
type: docs
url: /de/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Optionen zum Extrahieren von HTML aus dem Pptx-Text.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Gibt den Wert zurück oder legt ihn fest und gibt an, ob Clipboard-Kopfzeilen hinzugefügt werden sollen. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Gibt den Wert zurück oder legt ihn fest und gibt an, ob Clipboard-Kopfzeilen hinzugefügt werden sollen. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Gibt den Wert zurück oder legt ihn fest, die Vererbungstiefe für Texteigenschaften. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Gibt den Wert zurück oder legt ihn fest, die Vererbungstiefe für Texteigenschaften. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Gibt ein Callback-Objekt zurück oder legt es fest, das steuert, wie ein externes Objekt gespeichert wird. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Gibt ein Callback-Objekt zurück oder legt es fest, das steuert, wie ein externes Objekt gespeichert wird. |
| [getEncodingName()](#getEncodingName--) | Gibt den HTML-Kodierungsnamen zurück oder legt ihn fest. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Gibt den HTML-Kodierungsnamen zurück oder legt ihn fest. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

Gibt den Wert zurück oder legt ihn fest und gibt an, ob Clipboard-Kopfzeilen hinzugefügt werden sollen. Lesen/Schreiben boolean.

**Returns:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

Gibt den Wert zurück oder legt ihn fest und gibt an, ob Clipboard-Kopfzeilen hinzugefügt werden sollen. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

Gibt den Wert zurück oder legt ihn fest, die Vererbungstiefe für Texteigenschaften. Lesen/Schreiben [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Returns:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

Gibt den Wert zurück oder legt ihn fest, die Vererbungstiefe für Texteigenschaften. Lesen/Schreiben [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

Gibt ein Callback-Objekt zurück oder legt es fest, das steuert, wie ein externes Objekt gespeichert wird. Lesen/Schreiben [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returns:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

Gibt ein Callback-Objekt zurück oder legt es fest, das steuert, wie ein externes Objekt gespeichert wird. Lesen/Schreiben [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

Gibt den HTML-Kodierungsnamen zurück oder legt ihn fest. Dieser Wert wird in die erzeugte HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Kodierung gespeichert wird. Lesen/Schreiben String.

**Returns:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

Gibt den HTML-Kodierungsnamen zurück oder legt ihn fest. Dieser Wert wird in die erzeugte HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Kodierung gespeichert wird. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |