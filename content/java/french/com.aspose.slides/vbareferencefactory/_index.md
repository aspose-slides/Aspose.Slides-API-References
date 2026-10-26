---
title: VbaReferenceFactory
second_title: Référence de l'API Aspose.Slides pour Java
description: Permet de créer des références de projet VBA via l'interface COM
type: docs
url: /fr/com.aspose.slides/vbareferencefactory/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
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
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Crée une nouvelle référence à une bibliothèque de types OLE Automation. |
### VbaReferenceFactory() {#VbaReferenceFactory--}
```
public VbaReferenceFactory()
```


### getInstance() {#getInstance--}
```
public static VbaReferenceFactory getInstance()
```


Instance statique de la fabrique de références de projet VBA. Lecture seule [VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory).

**Retour :**
[VbaReferenceFactory](../../com.aspose.slides/vbareferencefactory)
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public final IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```


Crée une nouvelle référence à une bibliothèque de types OLE Automation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| libid | java.lang.String |  |

**Retour :**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nouvelle référence à une bibliothèque de types OLE Automation