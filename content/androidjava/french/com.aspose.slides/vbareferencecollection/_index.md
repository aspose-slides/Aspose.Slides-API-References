---
title: VbaReferenceCollection
second_title: Aspose.Slides pour Android via l'API Java
description: Représente une collection de références de projet VBA.
type: docs
url: /fr/com.aspose.slides/vbareferencecollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

Représente une collection de références de projet VBA.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int. |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | Ajoute la nouvelle référence à la collection de références |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean. |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### size() {#size--}
```
public final int size()
```


Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Retour :**
int
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```


Ajoute la nouvelle référence à la collection de références

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```


Obtient l'élément à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IVbaReference](../../com.aspose.slides/ivbareference)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - An java.util.Iterator for the entire collection.
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


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Retour :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie une racine de synchronisation. Lecture seule Object.

**Retour :**
java.lang.Object