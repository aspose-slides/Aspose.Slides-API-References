---
title: IVbaReferenceFactory
second_title: Aspose.Slides pour Android via la référence API Java
description: Permet de créer des références de projet VBA via l'interface COM
type: docs
url: /fr/com.aspose.slides/ivbareferencefactory/
---```
public interface IVbaReferenceFactory
```

Permet de créer des références de projet VBA via l'interface COM
## Méthodes

| Méthode | Description |
| --- | --- |
| [createOleTypeLibReference(String name, String libid)](#createOleTypeLibReference-java.lang.String-java.lang.String-) | Crée une nouvelle référence de bibliothèque de types OLE Automation. |
### createOleTypeLibReference(String name, String libid) {#createOleTypeLibReference-java.lang.String-java.lang.String-}
```
public abstract IVbaReferenceOleTypeLib createOleTypeLibReference(String name, String libid)
```

Crée une nouvelle référence de bibliothèque de types OLE Automation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la référence du projet VBA String |
| libid | java.lang.String | Identifiant d'une bibliothèque de types Automation String |

**Valeur de retour :**
[IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib) - Nouvelle référence de bibliothèque de types OLE Automation [IVbaReferenceOleTypeLib](../../com.aspose.slides/ivbareferenceoletypelib)