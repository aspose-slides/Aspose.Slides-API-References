---
title: VbaModuleCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de modules de projet VBA.
type: docs
url: /fr/com.aspose.slides/vbamodulecollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Représente une collection de modules de projet VBA.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Supprime la première occurrence d’un objet spécifique de la collection. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Ajoute un nouveau module vide au projet VBA. |
| [get_Item(int index)](#get-Item-int-) | Obtient l’élément à l’indice spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l’ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### size() {#size--}
```
public final int size()
```

Obtient le nombre d’éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie :**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

Supprime la première occurrence d’un objet spécifique de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Le module à supprimer de la collection. |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

Ajoute un nouveau module vide au projet VBA.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom du module |

**Renvoie :**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Module ajouté.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

Obtient l’élément à l’indice spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

Renvoie un itérateur java pour l’ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - un java.util.Iterator pour l’ensemble de la collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Indice de départ dans le tableau cible. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie :**
java.lang.Object