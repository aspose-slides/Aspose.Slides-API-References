---
title: RowCollection
second_title: Référence API Java pour Aspose.Slides sur Android
description: Représente la collection de lignes de tableau.
type: docs
url: /fr/com.aspose.slides/rowcollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Représente la collection de lignes de tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre de lignes réellement contenues dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie la ligne à l'index spécifié. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Crée une copie de la ligne modèle spécifiée et l'insère au bas d'un tableau. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Crée une copie de la ligne modèle spécifiée et l'insère à la position indiquée dans un tableau. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Supprime une ligne à la position spécifiée d'un tableau. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie la racine de synchronisation. |
### size() {#size--}
```
public final int size()
```

Obtient le nombre de lignes réellement contenues dans la collection. Lecture seule int.

**Retour :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Renvoie la ligne à l'index spécifié. Lecture seule [Row](../../com.aspose.slides/row).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Crée une copie de la ligne modèle spécifiée et l'insère au bas d'un tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | True pour copier également toutes les lignes attachées à la ligne modèle. |

**Retour :**
com.aspose.slides.IRow[] - Lignes ajoutées.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Crée une copie de la ligne modèle spécifiée et l'insère à la position indiquée dans un tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une nouvelle ligne. |
| templ | [IRow](../../com.aspose.slides/irow) | Ligne utilisée comme modèle. |
| withAttachedRows | boolean | True pour copier également toutes les lignes attachées à la ligne modèle. |

**Retour :**
com.aspose.slides.IRow[] - Lignes insérées.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Supprime une ligne à la position spécifiée d'un tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Index d'une ligne à supprimer. |
| withAttachedRows | boolean | True pour supprimer également toutes les lignes attachées. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Un java.util.Iterator pour l'ensemble de la collection.
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

Renvoie la racine de synchronisation. Lecture seule Object.

**Retour :**
java.lang.Object