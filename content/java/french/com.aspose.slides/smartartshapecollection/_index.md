---
title: SmartArtShapeCollection
second_title: Référence API Aspose.Slides pour Java
description: Représente une collection de formes SmartArt
type: docs
url: /fr/com.aspose.slides/smartartshapecollection/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

Représente une collection de formes SmartArt
## Méthodes

| Méthode | Description |
| --- | --- |
| [size()](#size--) | Obtient le nombre d'éléments réellement contenus dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Obtient l'élément à l'index spécifié. |
| [isSynchronized()](#isSynchronized--) | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Renvoie une racine de synchronisation. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copie tous les éléments de la collection dans le tableau spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### size() {#size--}
```
public final int size()
```


Obtient le nombre d'éléments réellement contenus dans la collection. Lecture seule int.

**Renvoie:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```


Obtient l'élément à l'index spécifié. Lecture seule [SmartArtShape](../../com.aspose.slides/smartartshape).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la forme |
**Renvoie:**  
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - La forme SmartArt
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). Lecture seule boolean.

**Renvoie:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Renvoie une racine de synchronisation. Lecture seule Object.

**Renvoie:**  
java.lang.Object
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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```


Renvoie un énumérateur qui parcourt la collection.

**Renvoie:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```


Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - Un java.util.Iterator pour l'ensemble de la collection.