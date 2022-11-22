---
title: WebDocument
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a transition form of the presentation for saving into a web format.
type: docs
weight: 615
url: /androidjava/com.aspose.slides/webdocument/
---
**Inheritance:**
java.lang.Object
```
public class WebDocument
```

Represents a transition form of the presentation for saving into a web format.
## Constructors

| Constructor | Description |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) constructor. |
## Methods

| Method | Description |
| --- | --- |
| [save()](#save--) | Saves the document output. |
| [getInput()](#getInput--) | Returns collection of input elements (templates) of the document. |
| [getOutput()](#getOutput--) | Returns collection of output elements of the document. |
| [getGlobal()](#getGlobal--) | Returns global storage of the document. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Options set for the document. |

### save() {#save--}
```
public final void save()
```


Saves the document output.

### getInput() {#getInput--}
```
public final Input getInput()
```


Returns collection of input elements (templates) of the document. Read-only [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Returns:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Returns collection of output elements of the document. Read-only [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // put "slideMargin" property to use from templates
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... set up other options of the document and then save the document
>   document.save();
> ```

**Returns:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Returns global storage of the document. Read-only [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // put "slideMargin" property to use from templates
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... set up other options of the document and then save the document
>   document.save();
> ```

**Returns:**
[Storage](../../com.aspose.slides/storage)
