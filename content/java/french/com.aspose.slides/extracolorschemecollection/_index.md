---
title: ExtraColorSchemeCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection de schémas de couleurs supplémentaires.
type: docs
url: /fr/com.aspose.slides/extracolorschemecollection/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Représente une collection de schémas de couleurs supplémentaires.
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Retourne le nombre d'éléments dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Retourne un jeu de couleurs par index. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Retourne un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Retourne un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Retourne une valeur indiquant si l'accès à l'ArrayList est synchronisé (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourne un objet pouvant être utilisé pour synchroniser l'accès à la collection. |
### size() {#size--}
```
public final int size()
```

Retourne le nombre d'éléments dans la collection. Lecture seule int.

**Retourne:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Retourne un jeu de couleurs par index. Lecture seule [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourne:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourne l'objet Parent_Immediate. Lecture seule IDOMObject.

**Retourne:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Retourne un énumérateur qui parcourt la collection.

**Retourne:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Retourne un itérateur java pour l'ensemble de la collection.

**Retourne:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tableau cible. |
| index | int | Indice de départ dans le tableau. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourne une valeur indiquant si l'accès à l'ArrayList est synchronisé (thread safe). Lecture seule boolean.

**Retourne:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourne un objet pouvant être utilisé pour synchroniser l'accès à la collection. Lecture seule Object.

Retourne une racine de synchronisation. Lecture seule Object.

**Retourne:**
java.lang.Object