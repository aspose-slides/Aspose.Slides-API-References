---
title: WebDocument
second_title: Aspose.Slides Java API hivatkozás
description: A bemutató webformátumba történő mentéséhez egy átmeneti formátumot képvisel.
type: docs
url: /hu/com.aspose.slides/webdocument/
---
**Öröklés:**
java.lang.Object
```
public class WebDocument
```

A bemutató webformátumba történő mentéséhez egy átmeneti formátumot képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) konstruktor. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [save()](#save--) | Mentse a dokumentum kimenetét. |
| [getInput()](#getInput--) | Visszaadja a dokumentum bemeneti elemek (sablonok) gyűjteményét. |
| [getOutput()](#getOutput--) | Visszaadja a dokumentum kimeneti elemek gyűjteményét. |
| [getGlobal()](#getGlobal--) | Visszaadja a dokumentum globális tárolóját. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) konstruktor.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | A dokumentumra vonatkozó beállítások. |

### save() {#save--}
```
public final void save()
```


Mentse a dokumentum kimenetét.

### getInput() {#getInput--}
```
public final Input getInput()
```


Visszaadja a dokumentum bemeneti elemek (sablonok) gyűjteményét. Csak olvasható [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Visszatérési érték:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Visszaadja a dokumentum kimeneti elemek gyűjteményét. Csak olvasható [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // helyezze be a "slideMargin" tulajdonságot a sablonok használatához
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... állítsa be a dokumentum egyéb beállításait, majd mentse a dokumentumot
>   document.save();
> ```

**Visszatérési érték:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Visszaadja a dokumentum globális tárolóját. Csak olvasható [Storage](../../com.aspose.slides/storage).

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

**Visszatérési érték:**
[Storage](../../com.aspose.slides/storage)