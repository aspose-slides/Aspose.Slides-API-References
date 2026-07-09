---
title: IVbaModuleCollection
second_title: Aspose.Slides pour Android via l'API Java
description: Représente une collection de modules d'un projet VBA.
type: docs
url: /fr/com.aspose.slides/ivbamodulecollection/
---
**Toutes les interfaces implémentées :**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

Représente une collection de modules d'un projet VBA.
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Ajoute un nouveau module vide au projet VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Supprime la première occurrence d'un objet spécifique de la collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```


Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Valeur de retour :**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```


Ajoute un nouveau module vide au projet VBA.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom du module |

**Valeur de retour :**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Module ajouté.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```


Supprime la première occurrence d'un objet spécifique de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Le module à supprimer de la collection. |
