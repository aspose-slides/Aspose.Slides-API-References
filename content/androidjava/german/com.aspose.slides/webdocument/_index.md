---
title: WebDocument
second_title: Aspose.Slides für Android via Java API-Referenz
description: Stellt eine Übergangsform der Präsentation zum Speichern in einem Webformat dar.
type: docs
url: /de/com.aspose.slides/webdocument/
---
**Vererbung:**
java.lang.Object
```
public class WebDocument
```

Stellt eine Übergangsform der Präsentation zum Speichern in einem Webformat dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [save()](#save--) | Speichert die Dokumentausgabe. |
| [getInput()](#getInput--) | Gibt die Sammlung von Eingabeelementen (Vorlagen) des Dokuments zurück. |
| [getOutput()](#getOutput--) | Gibt die Sammlung von Ausgabeelementen des Dokuments zurück. |
| [getGlobal()](#getGlobal--) | Gibt den globalen Speicher des Dokuments zurück. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) Konstruktor.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Optionen für das Dokument festgelegt. |

### save() {#save--}
```
public final void save()
```


Speichert die Dokumentausgabe.

### getInput() {#getInput--}
```
public final Input getInput()
```


Gibt die Sammlung von Eingabeelementen (Vorlagen) des Dokuments zurück. Nur lesbar [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Rückgabewert:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Gibt die Sammlung von Ausgabeelementen des Dokuments zurück. Nur lesbar [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // setze die Eigenschaft "slideMargin" zur Verwendung aus Vorlagen
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... weitere Optionen des Dokuments einrichten und dann das Dokument speichern
>   document.save();
> ```

**Rückgabewert:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Gibt den globalen Speicher des Dokuments zurück. Nur lesbar [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // setze die Eigenschaft "slideMargin" zur Verwendung aus Vorlagen
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... weitere Optionen des Dokuments einrichten und dann das Dokument speichern
>   document.save();
> ```

**Rückgabewert:**
[Storage](../../com.aspose.slides/storage)