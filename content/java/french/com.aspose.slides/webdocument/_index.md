---
title: WebDocument
second_title: Référence API Aspose.Slides pour Java
description: Représente une forme de transition de la présentation pour l'enregistrement dans un format web.
type: docs
url: /fr/com.aspose.slides/webdocument/
---
**Héritage:**
java.lang.Object
```
public class WebDocument
```

Représente une forme de transition de la présentation pour l'enregistrement dans un format web.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) constructeur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [save()](#save--) | Enregistre la sortie du document. |
| [getInput()](#getInput--) | Renvoie la collection des éléments d'entrée (modèles) du document. |
| [getOutput()](#getOutput--) | Renvoie la collection des éléments de sortie du document. |
| [getGlobal()](#getGlobal--) | Renvoie le stockage global du document. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) constructeur.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Options définies pour le document. |

### save() {#save--}
```
public final void save()
```

Enregistre la sortie du document.

### getInput() {#getInput--}
```
public final Input getInput()
```

Renvoie la collection des éléments d'entrée (modèles) du document. Lecture seule [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Renvoie :**
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
>   // mettre la propriété "slideMargin" à utiliser depuis les modèles
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... configurer d'autres options du document puis enregistrer le document
>   document.save();
> ```


**Renvoie :**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Renvoie le stockage global du document. Lecture seule [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> En utilisant cette propriété (#getGlobal.getGlobal) (implémentation de l'interface [Storage](../../com.aspose.slides/storage)) une
>   propriété peut être mise en place pour l'utiliser plus tard dans le modèle :
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // mettre la propriété "slideMargin" à utiliser depuis les modèles
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... configurer d'autres options du document puis enregistrer le document
>   document.save();
> ```

**Renvoie :**
[Storage](../../com.aspose.slides/storage)