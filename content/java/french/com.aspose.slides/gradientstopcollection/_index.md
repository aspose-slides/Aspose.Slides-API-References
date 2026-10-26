---
title: GradientStopCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une collection d'arrêts de gradient.
type: docs
url: /fr/com.aspose.slides/gradientstopcollection/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées :**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Représente une collection d'arrêts de gradient.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Renvoie le nombre d'arrêts de gradient dans une collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'arrêt de gradient par indice. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Crée le nouvel arrêt de gradient et l'ajoute à la fin de la collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crée le nouvel arrêt de gradient et l'ajoute à la fin de la collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crée le nouvel arrêt de gradient et l'ajoute à la fin de la collection. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Crée le nouvel arrêt de gradient et l'insère à l'indice spécifié dans la collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crée le nouvel arrêt de gradient et l'insère à l'indice spécifié dans la collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crée le nouvel arrêt de gradient et l'insère à l'indice spécifié dans la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un arrêt de gradient à l'indice spécifié. |
| [clear()](#clear--) | Supprime tous les arrêts de gradient d'une collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Long en lecture seule.

**Renvoie :**
long
### size() {#size--}
```
public final int size()
```


Renvoie le nombre d'arrêts de gradient dans une collection. Int en lecture seule.

**Renvoie :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Renvoie l'arrêt de gradient par indice.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int |  |

**Renvoie :**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public final IGradientStop add(float position, Color color)
```


Crée le nouvel arrêt de gradient et l'ajoute à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouvel arrêt de gradient. |
| color | java.awt.Color | Couleur du nouvel arrêt de gradient. |

**Renvoie :**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice du nouvel arrêt de gradient dans la collection.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Crée le nouvel arrêt de gradient et l'ajoute à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouvel arrêt de gradient. |
| presetColor | int | Couleur du nouvel arrêt de gradient. |

**Renvoie :**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice du nouvel arrêt de gradient dans la collection.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Crée le nouvel arrêt de gradient et l'ajoute à la fin de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| position | float | Position du nouvel arrêt de gradient. |
| schemeColor | int | Couleur du nouvel arrêt de gradient. |

**Renvoie :**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice du nouvel arrêt de gradient dans la collection.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public final void insert(int index, float position, Color color)
```


Crée le nouvel arrêt de gradient et l'insère à l'indice spécifié dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice dans la collection où le nouvel arrêt de gradient sera inséré. |
| position | float | Position du nouvel arrêt de gradient. |
| color | java.awt.Color | Couleur du nouvel arrêt de gradient. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Crée le nouvel arrêt de gradient et l'insère à l'indice spécifié dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice dans la collection où le nouvel arrêt de gradient sera inséré. |
| position | float | Position du nouvel arrêt de gradient. |
| presetColor | int | Couleur du nouvel arrêt de gradient. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Crée le nouvel arrêt de gradient et l'insère à l'indice spécifié dans la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice dans la collection où le nouvel arrêt de gradient sera inséré. |
| position | float | Position du nouvel arrêt de gradient. |
| schemeColor | int | Couleur du nouvel arrêt de gradient. |

### removeAt(int index) {#removeAt-int-}
```java
public final void removeAt(int index)
```


Supprime un arrêt de gradient à l'indice spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Indice d'un arrêt de gradient qui doit être supprimé. |

### clear() {#clear--}
```
public final void clear()
```


Supprime tous les arrêts de gradient d'une collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator for the entire collection.
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


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Boolean en lecture seule.

**Renvoie :**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie une racine de synchronisation. Object en lecture seule.

**Renvoie :**
java.lang.Object