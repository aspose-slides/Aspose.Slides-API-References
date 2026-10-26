---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /de/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Optionen zum Extrahieren von HTML aus dem Pptx-Text.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Clipboard-Header hinzugefügt werden sollen. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Clipboard-Header hinzugefügt werden sollen. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Gibt die Vererbungstiefe für Texteigenschaften zurück oder setzt sie. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Gibt die Vererbungstiefe für Texteigenschaften zurück oder setzt sie. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Gibt das Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Gibt das Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. |
| [getEncodingName()](#getEncodingName--) | Gibt den HTML-Codierungsnamen zurück oder setzt ihn. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Gibt den HTML-Codierungsnamen zurück oder setzt ihn. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Clipboard-Header hinzugefügt werden sollen. Lese/Schreib boolean.

**Rückgabe:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


Gibt den Wert zurück oder setzt ihn, wobei angegeben wird, ob Clipboard-Header hinzugefügt werden sollen. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


Gibt die Vererbungstiefe für Texteigenschaften zurück oder setzt sie. Lese/Schreib [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Rückgabe:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


Gibt die Vererbungstiefe für Texteigenschaften zurück oder setzt sie. Lese/Schreib [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


Gibt das Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. Lese/Schreib [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Rückgabe:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


Gibt das Callback-Objekt zurück oder setzt es, das steuert, wie ein externes Objekt gespeichert wird. Lese/Schreib [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


Gibt den HTML-Codierungsnamen zurück oder setzt ihn. Dieser Wert wird in die erzeugte HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Codierung gespeichert wird. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


Gibt den HTML-Codierungsnamen zurück oder setzt ihn. Dieser Wert wird in die erzeugte HTML-Datei gespeichert, aber es liegt am Aufrufer sicherzustellen, dass die Datei in dieser Codierung gespeichert wird. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |