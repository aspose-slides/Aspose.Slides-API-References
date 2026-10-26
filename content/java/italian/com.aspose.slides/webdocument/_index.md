---
title: WebDocument
second_title: Aspose.Slides per Java Riferimento API
description: Rappresenta una forma di transizione della presentazione per il salvataggio in formato web.
type: docs
url: /it/com.aspose.slides/webdocument/
---
**Ereditarietà:**
java.lang.Object
```
public class WebDocument
```

Rappresenta una forma di transizione della presentazione per il salvataggio in formato web.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) costruttore. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [save()](#save--) | Salva l'output del documento. |
| [getInput()](#getInput--) | Restituisce la collezione di elementi di input (modelli) del documento. |
| [getOutput()](#getOutput--) | Restituisce la collezione di elementi di output del documento. |
| [getGlobal()](#getGlobal--) | Restituisce l'archivio globale del documento. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) costruttore.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Opzioni impostate per il documento. |

### save() {#save--}
```
public final void save()
```


Salva l'output del documento.

### getInput() {#getInput--}
```
public final Input getInput()
```


Restituisce la collezione di elementi di input (modelli) del documento. Solo lettura [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Restituisce:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Restituisce la collezione di elementi di output del documento. Solo lettura [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // inserisci la proprietà "slideMargin" da utilizzare nei modelli
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... imposta altre opzioni del documento e poi salva il documento
>   document.save();
> ```

**Restituisce:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Restituisce l'archivio globale del documento. Solo lettura [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // inserisci la proprietà "slideMargin" da utilizzare nei modelli
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... imposta altre opzioni del documento e poi salva il documento
>   document.save();
> ```

**Restituisce:**
[Storage](../../com.aspose.slides/storage)