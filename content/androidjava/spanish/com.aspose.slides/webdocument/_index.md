---
title: WebDocument
second_title: Aspose.Slides para Android a través de la Referencia de la API Java
description: Representa una forma de transición de la presentación para guardarla en un formato web.
type: docs
url: /es/com.aspose.slides/webdocument/
---
**Herencia:**
java.lang.Object
```
public class WebDocument
```

Representa una forma de transición de la presentación para guardarla en un formato web.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) constructor. |
## Métodos

| Método | Descripción |
| --- | --- |
| [save()](#save--) | Guarda la salida del documento. |
| [getInput()](#getInput--) | Devuelve la colección de elementos de entrada (plantillas) del documento. |
| [getOutput()](#getOutput--) | Devuelve la colección de elementos de salida del documento. |
| [getGlobal()](#getGlobal--) | Devuelve el almacenamiento global del documento. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) constructor.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Opciones establecidas para el documento. |

### save() {#save--}
```
public final void save()
```


Guarda la salida del documento.

### getInput() {#getInput--}
```
public final Input getInput()
```


Devuelve la colección de elementos de entrada (plantillas) del documento. Solo lectura [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Devuelve:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Devuelve la colección de elementos de salida del documento. Solo lectura [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // establecer la propiedad "slideMargin" para usar desde plantillas
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... configurar otras opciones del documento y luego guardar el documento
>   document.save();
> ```

**Devuelve:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Devuelve el almacenamiento global del documento. Solo lectura [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // poner la propiedad "slideMargin" para usarla desde plantillas
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... configurar otras opciones del documento y luego guardar el documento
>   document.save();
> ```

**Devuelve:**
[Storage](../../com.aspose.slides/storage)