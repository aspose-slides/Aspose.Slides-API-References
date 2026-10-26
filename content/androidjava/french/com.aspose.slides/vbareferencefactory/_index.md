---
title: VbaReferenceFactory
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Permet de créer des références de projet VBA via l'interface COM
type: docs
url: /fr/com.aspose.slides/vbareferencefactory/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IVbaReferenceFactory](../../com.aspose.slides/ivbareferencefactory)  
```
public class VbaReferenceFactory implements IVbaReferenceFactory
```

Permet de créer des références de projet VBA via l'interface COM
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VbaReferenceFactory()](#VbaReferenceFactory--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInstance()](#getInstance--) | Instance statique de la fabrique de références de projet VBA. |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Crée une nouvelle référence de bibliothèque de type OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Instance statique de la fabrique de références de projet VBA. Lecture seule [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Renvoie:**  
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Crée une nouvelle référence de bibliothèque de type OLE Automation.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Renvoie:**  
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nouvelle référence de bibliothèque de type OLE Automation