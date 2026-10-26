---
title: WebDocument
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une forme de transition de la présentation pour l'enregistrement au format web.
type: docs
url: /fr/com.aspose.slides/webdocument/
---
**Héritage :**
java.lang.Object
```
public class WebDocument
```

Représente une forme de transition de la présentation pour l’enregistrer au format web.
## Constructeurs

| Constructor | Description |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) constructeur. |
## Méthodes

| Method | Description |
| --- | --- |
| [save()](#save--) | Renvoie le stockage du document. |
| [getInput()](#getInput--) | Renvoie la collection des éléments d'entrée (modèles) du document. |
| [getOutput()](#getOutput--) | Renvoie la collection des éléments de sortie du document. |
| [getGlobal()](#getGlobal--) | Renvoie le stockage global du document. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) constructeur.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Options définies pour le document. |

### save() {#save--}
```
public final void save()
```


Renvoie le stockage du document.

### getInput() {#getInput--}
```
public final Input getInput()
```


Renvoie la collection des éléments d'entrée (modèles) du document. Lecture seule [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Retour :**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Renvoie la collection des éléments de sortie du document. Lecture seule [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

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


Renvoie le stockage global du document. Lecture seule [Storage](../../com.aspose.slides/storage).

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

**Retour :**
[Storage](../../com.aspose.slides/storage)