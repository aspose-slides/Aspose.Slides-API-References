---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides für Java API Referenz
description: Optionen zum Extrahieren von HTML aus dem Pptx-Text.
type: docs
url: /de/com.aspose.slides/texttohtmlconversionoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Optionen zum Extrahieren von HTML aus dem Pptx-Text.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Gibt den Wert zurück oder setzt ihn und zeigt an, ob Clipboard-Header hinzugefügt werden sollen. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Gibt den Wert zurück oder setzt ihn und zeigt an, ob Clipboard-Header hinzugefügt werden sollen. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Gibt die geerbte Tiefe für Texteigenschaften zurück oder setzt sie. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Gibt die geerbte Tiefe für Texteigenschaften zurück oder setzt sie. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. |
| [getEncodingName()](#getEncodingName--) | Gibt den HTML-Kodierungsnamen zurück oder setzt ihn. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Gibt den HTML-Kodierungsnamen zurück oder setzt ihn. |

### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```

Gibt den Wert zurück oder setzt ihn und zeigt an, ob Clipboard-Header hinzugefügt werden sollen. Lese-/Schreib-boolean.

**Returns:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

Gibt den Wert zurück oder setzt ihn und zeigt an, ob Clipboard-Header hinzugefügt werden sollen. Lese-/Schreib-boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

Gibt die geerbte Tiefe für Texteigenschaften zurück oder setzt sie. Lese-/Schreib-[TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Returns:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

Gibt die geerbte Tiefe für Texteigenschaften zurück oder setzt sie. Lese-/Schreib-[TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. Lese-/Schreib-[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Returns:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. Lese-/Schreib-[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

Gibt den HTML-Kodierungsnamen zurück oder setzt ihn. Dieser Wert wird in die erzeugte HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Kodierung gespeichert wird. Lese-/Schreib-String.

**Returns:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

Gibt den HTML-Kodierungsnamen zurück oder setzt ihn. Dieser Wert wird in die erzeugte HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Kodierung gespeichert wird. Lese-/Schreib-String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |