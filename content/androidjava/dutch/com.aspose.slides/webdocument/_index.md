---
title: WebDocument
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een overgangsvorm van de presentatie voor het opslaan in een webformaat.
type: docs
url: /nl/com.aspose.slides/webdocument/
---
**Erfelijkheid:**
java.lang.Object
```
public class WebDocument
```

Vertegenwoordigt een overgangsvorm van de presentatie voor het opslaan in een webformaat.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) constructor. |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [save()](#save--) | Slaat de documentuitvoer op. |
| [getInput()](#getInput--) | Retourneert de collectie invoerelementen (sjablonen) van het document. |
| [getOutput()](#getOutput--) | Retourneert de collectie uitvoerelementen van het document. |
| [getGlobal()](#getGlobal--) | Retourneert de globale opslag van het document. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) constructor.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Opties ingesteld voor het document. |

### save() {#save--}
```
public final void save()
```

Slaat de documentuitvoer op.

### getInput() {#getInput--}
```
public final Input getInput()
```

Retourneert de collectie invoerelementen (sjablonen) van het document. Alleen-lezen [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Retourneert:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Retourneert de collectie uitvoerelementen van het document. Alleen-lezen [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // zet de "slideMargin" eigenschap om te gebruiken vanuit sjablonen
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... stel andere opties van het document in en sla vervolgens het document op
>   document.save();
> ```

**Retourneert:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Retourneert de globale opslag van het document. Alleen-lezen [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // zet "slideMargin" eigenschap om te gebruiken vanuit sjablonen
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... stel andere opties van het document in en sla vervolgens het document op
>   document.save();
> ```

**Retourneert:**
[Storage](../../com.aspose.slides/storage)