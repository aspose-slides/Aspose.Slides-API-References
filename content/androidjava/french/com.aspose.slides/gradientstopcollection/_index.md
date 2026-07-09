---
title: GradientStopCollection
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente une collection d'arrêts de dégradé.
type: docs
url: /fr/com.aspose.slides/gradientstopcollection/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)  
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Représente une collection d'arrêts de dégradé.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Renvoie le nombre d'arrêts de dégradé dans une collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie l'arrêt de dégradé à l'index donné. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime un arrêt de dégradé à l'index spécifié. |
| [clear()](#clear--) | Supprime tous les arrêts de dégradé d'une collection. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur Java pour toute la collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**  
long

### size() {#size--}
```
public final int size()
```

Renvoie le nombre d'arrêts de dégradé dans une collection. Lecture seule int.

**Renvoie :**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Renvoie l'arrêt de dégradé à l'index.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
index | int |  

**Renvoie :**  
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
position | float | Position du nouvel arrêt de dégradé.  
color | java.lang.Integer | Couleur du nouvel arrêt de dégradé.  

**Renvoie :**  
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouvel arrêt de dégradé dans la collection.

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
position | float | Position du nouvel arrêt de dégradé.  
presetColor | int | Couleur du nouvel arrêt de dégradé.  

**Renvoie :**  
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouvel arrêt de dégradé dans la collection.

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Crée le nouvel arrêt de dégradé et l'ajoute à la fin de la collection.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
position | float | Position du nouvel arrêt de dégradé.  
schemeColor | int | Couleur du nouvel arrêt de dégradé.  

**Renvoie :**  
[IGradientStop](../../com.aspose.slides/igradientstop) - Index du nouvel arrêt de dégradé dans la collection.

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
index | int | Index dans la collection où le nouvel arrêt de dégradé sera inséré.  
position | float | Position du nouvel arrêt de dégradé.  
color | java.lang.Integer | Couleur du nouvel arrêt de dégradé.  

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
index | int | Index dans la collection où le nouvel arrêt de dégradé sera inséré.  
position | float | Position du nouvel arrêt de dégradé.  
presetColor | int | Couleur du nouvel arrêt de dégradé.  

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Crée le nouvel arrêt de dégradé et l'insère à l'index spécifié dans la collection.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
index | int | Index dans la collection où le nouvel arrêt de dégradé sera inséré.  
position | float | Position du nouvel arrêt de dégradé.  
schemeColor | int | Couleur du nouvel arrêt de dégradé.  

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime un arrêt de dégradé à l'index spécifié.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
index | int | Index d'un arrêt de dégradé qui doit être supprimé.  

### clear() {#clear--}
```
public final void clear()
```

Supprime tous les arrêts de dégradé d'une collection.

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

Renvoie un itérateur Java pour toute la collection.

**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copie tous les éléments de la collection dans le tableau spécifié.

**Paramètre** | **Type** | **Description**  
--- | --- | ---  
array | com.aspose.ms.System.Array | Tableau cible.  
index | int | Index de départ dans le tableau cible.  

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie :**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie :**  
java.lang.Object