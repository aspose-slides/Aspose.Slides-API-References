---
title: TabCollection
second_title: Référence API Aspose.Slides pour Android via Java
description: Représente une collection d'onglets.
type: docs
url: /fr/com.aspose.slides/tabcollection/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Représente une collection d'onglets.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [add(double position, int align)](#add-double-int-) | Ajoute un onglet à la collection. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Ajoute un onglet à la collection. |
| [clear()](#clear--) | Supprime tous les éléments de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime l'élément à l'index spécifié de la collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si deux instances de TabsEx sont égales. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l’ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### size() {#size--}
```
public final int size()
```

Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```

Obtient l'élément à l'index spécifié. Lecture seule [Tab](../../com.aspose.slides/tab).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```

Ajoute un onglet à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Renvoie:**
[ITab](../../com.aspose.slides/itab) - Onglet ajouté.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```

Ajoute un onglet à la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | L'objet Tab à ajouter à la fin de la collection. |

**Renvoie:**
int - L'index où l'onglet a été ajouté.
### clear() {#clear--}
```
public final void clear()
```

Supprime tous les éléments de la collection.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime l'élément à l'index spécifié de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro de l'élément à supprimer. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Détermine si deux instances de TabsEx sont égales.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le TabsEx à comparer avec le TabsEx actuel. |

**Renvoie:**
boolean - **true** si le TabsEx spécifié est égal au TabsEx actuel ; sinon, **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```

Renvoie un itérateur java pour l’ensemble de la collection.

**Renvoie:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - Un java.util.Iterator pour l’ensemble de la collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Index de départ dans le tableau cible. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l’accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie:**
java.lang.Object