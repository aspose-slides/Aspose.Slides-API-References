---
title: ColorOperationCollection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une collection d'opérations de transformation de couleur.
type: docs
url: /fr/com.aspose.slides/coloroperationcollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Représente une collection d'opérations de transformation de couleur.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Renvoie le nombre d'opérations dans une collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie ou définit l'opération à l'index spécifié. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Renvoie ou définit l'opération à l'index spécifié. |
| [add(int operation, float parameter)](#add-int-float-) | Ajoute une nouvelle opération à la fin de la collection. |
| [add(int operation)](#add-int-) | Ajoute une nouvelle opération à la fin de la collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Insère la nouvelle opération dans une collection. |
| [insert(int position, int operation)](#insert-int-int-) | Insère la nouvelle opération dans une collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'opération de couleur d'une collection. |
| [clear()](#clear--) | Supprime toutes les opérations de couleur. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [deepClone()](#deepClone--) | Crée une copie d'une collection ColorOperationCollection. |
| [cloneT()](#cloneT--) | Clone l'objet courant |
### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'opérations dans une collection. Lecture seule int.

**Retour :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Renvoie ou définit l'opération à l'index spécifié. Lecture/écriture [ColorOperation](../../com.aspose.slides/coloroperation).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour :**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

Renvoie ou définit l'opération à l'index spécifié. Lecture/écriture [ColorOperation](../../com.aspose.slides/coloroperation).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |
### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Ajoute une nouvelle opération à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operation | int | Type d'opération. |
| parameter | float | Paramètre de l'opération. |

**Retour :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération ajoutée.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Ajoute une nouvelle opération à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| operation | int | Type d'opération. |

**Retour :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération ajoutée.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Insère la nouvelle opération dans une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | int | L'index auquel l'opération sera insérée. |
| operation | int | Type d'opération. |
| parameter | float | Paramètre de l'opération. |

**Retour :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération insérée.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Insère la nouvelle opération dans une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | int | L'index auquel l'opération sera insérée. |
| operation | int | Type d'opération. |

**Retour :**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Opération insérée.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'opération de couleur d'une collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une opération de couleur à supprimer. |
### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les opérations de couleur.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Renvoie un itérateur Java pour l'ensemble de la collection.

**Retour :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Un java.util.Iterator pour l'ensemble de la collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |
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
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Crée une copie d'une collection ColorOperationCollection.

**Retour :**
java.lang.Object - Nouvelle collection [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection)
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Clone l'objet courant

**Retour :**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Clone