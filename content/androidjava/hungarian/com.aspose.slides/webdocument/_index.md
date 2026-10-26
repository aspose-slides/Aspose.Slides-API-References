---
title: WebDocument
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A prezentáció webformátumba mentésére szolgáló átmeneti formátumot képviseli.
type: docs
url: /hu/com.aspose.slides/webdocument/
---
**Öröklés:**
java.lang.Object
```
public class WebDocument
```

A prezentáció webformátumba mentésére szolgáló átmeneti formátumot képviseli.
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) constructor. |
## Methods

| Metódus | Leírás |
| --- | --- |
| [save()](#save--) | Saves the document output. |
| [getInput()](#getInput--) | Returns collection of input elements (templates) of the document. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the document. |
| [getGlobal()](#getGlobal--) | Returns global storage of the document. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) konstruktor.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | A dokumentumhoz beállított beállítások. |

### save() {#save--}
```
public final void save()
```

Elmenti a dokumentum kimenetét.

### getInput() {#getInput--}
```
public final Input getInput()
```

Visszaadja a dokumentum bemeneti elemeinek (sablonok) gyűjteményét. Csak olvasható [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Visszatér:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Visszaadja a dokumentum kimeneti elemeinek gyűjteményét. Csak olvasható [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   //   helyezze be a "slideMargin" tulajdonságot a sablonok használatához
>   document.getGlobal().put("slideMargin", 10);
> 
>   //   ... állítsa be a dokumentum egyéb beállításait, majd mentse a dokumentumot
>   document.save();
> ```

**Visszatér:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Csak olvasható [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // helyezze be a "slideMargin" tulajdonságot a sablonok használatához
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... állítsa be a dokumentum egyéb beállításait, majd mentse a dokumentumot
>   document.save();
> ```

**Visszatér:**
[Storage](../../com.aspose.slides/storage)