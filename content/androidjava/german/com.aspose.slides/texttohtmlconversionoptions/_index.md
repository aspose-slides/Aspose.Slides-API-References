---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides für Android über die Java API Referenz
description: Optionen zum Extrahieren von HTML aus dem Pptx-Text.
type: docs
url: /de/com.aspose.slides/texttohtmlconversionoptions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Optionen zum Extrahieren von HTML aus dem Pptx-Text.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Zwischenablage-Header hinzugefügt werden sollen. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Zwischenablage-Header hinzugefügt werden sollen. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Gibt die Vererbungstiefe für Text-Eigenschaften zurück oder setzt sie. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Gibt die Vererbungstiefe für Text-Eigenschaften zurück oder setzt sie. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie externe Objekte gespeichert werden. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie externe Objekte gespeichert werden. |
| [getEncodingName()](#getEncodingName--) | Gibt den HTML-Codierungsnamen zurück oder setzt ihn. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Gibt den HTML-Codierungsnamen zurück oder setzt ihn. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```

### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```

Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Zwischenablage-Header hinzugefügt werden sollen. Lese-/Schreibboolesch.

**Rückgabe:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Zwischenablage-Header hinzugefügt werden sollen. Lese-/Schreibboolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

Gibt die Vererbungstiefe für Text-Eigenschaften zurück oder setzt sie. Lese-/Schreib [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Rückgabe:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

Gibt die Vererbungstiefe für Text-Eigenschaften zurück oder setzt sie. Lese-/Schreib [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie externe Objekte gespeichert werden. Lese-/Schreib [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Rückgabe:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

Gibt ein Callback-Objekt zurück oder setzt es, das steuert, wie externe Objekte gespeichert werden. Lese-/Schreib [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

Gibt den HTML-Codierungsnamen zurück oder setzt ihn. Dieser Wert wird in der erzeugten HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Codierung gespeichert wird. Lese-/Schreib String.

**Rückgabe:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

Gibt den HTML-Codierungsnamen zurück oder setzt ihn. Dieser Wert wird in der erzeugten HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Codierung gespeichert wird. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |