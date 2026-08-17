---
title: ColumnCollection
second_title: Référence API Aspose.Slides pour Java
description: Représente une collection de colonnes dans un tableau.
type: docs
url: /fr/com.aspose.slides/columncollection/
---
**Héritage :**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées :**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Représente une collection de colonnes dans un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre de colonnes dans une collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie la colonne à l’indice spécifié. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Crée une copie de la ligne modèle spécifiée et l’insère au bas d’un tableau. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Crée une copie de la colonne modèle spécifiée et l’insère à la position spécifiée dans un tableau. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Supprime une colonne à la position spécifiée d’un tableau. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l’ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre de colonnes dans une collection. Lecture seule int.

**Renvoie :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Renvoie la colonne à l’indice spécifié. Lecture seule [Column](../../com.aspose.slides/column).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Crée une copie de la ligne modèle spécifiée et l’insère au bas d’un tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonne utilisée comme modèle. |
| withAttachedColumns | boolean | Vrai pour copier également toutes les colonnes attachées à la ligne modèle. |

**Renvoie :**
com.aspose.slides.IColumn[] - Colonnes ajoutées.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Crée une copie de la colonne modèle spécifiée et l’insère à la position spécifiée dans un tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la nouvelle colonne. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonne utilisée comme modèle. |
| withAttachedColumns | boolean | Vrai pour copier également toutes les colonnes attachées à la colonne modèle. |

**Renvoie :**
com.aspose.slides.IColumn[] - Colonnes insérées.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Supprime une colonne à la position spécifiée d’un tableau.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Index de la colonne à supprimer. |
| withAttachedRows | boolean | Vrai pour supprimer également toutes les colonnes attachées. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Un IGenericEnumerator pouvant être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Renvoie un itérateur java pour l’ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Un java.util.Iterator pour l’ensemble de la collection.
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