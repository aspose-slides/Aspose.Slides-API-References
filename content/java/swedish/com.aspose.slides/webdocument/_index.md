---
title: WebDocument
second_title: Aspose.Slides för Java API-referens
description: Representerar en övergångsform av presentationen för att sparas i ett webbformat.
type: docs
url: /sv/com.aspose.slides/webdocument/
---
**Arv:**
java.lang.Object
```
public class WebDocument
```

Representerar en övergångsform av presentationen för att sparas i ett webbformat.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) konstruktor. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [save()](#save--) | Sparar dokumentutdata. |
| [getInput()](#getInput--) | Returnerar samling av indatatlement (mallar) i dokumentet. |
| [getOutput()](#getOutput--) | Returnerar samling av utdataelement i dokumentet. |
| [getGlobal()](#getGlobal--) | Returnerar global lagring av dokumentet. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) konstruktor.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Alternativ som är satta för dokumentet. |

### save() {#save--}
```
public final void save()
```


Sparar dokumentutdata.

### getInput() {#getInput--}
```
public final Input getInput()
```


Returnerar samling av indatatlement (mallar) i dokumentet. Skrivskyddad [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Returnerar:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Returnerar samling av utdataelement i dokumentet. Skrivskyddad [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // lägg till egenskapen "slideMargin" för att använda från mallar
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... konfigurera andra alternativ för dokumentet och sedan spara dokumentet
>   document.save();
> ```


**Returnerar:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Returnerar global lagring av dokumentet. Skrivskyddad [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // lägg till egenskapen "slideMargin" för att använda från mallar
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... konfigurera andra alternativ för dokumentet och sedan spara dokumentet
>   document.save();
> ```

**Returnerar:**
[Storage](../../com.aspose.slides/storage)