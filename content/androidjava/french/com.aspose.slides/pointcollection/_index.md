---
title: PointCollection
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente une collection de points d'animation.
type: docs
url: /fr/com.aspose.slides/pointcollection/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Représente une collection de points d'animation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCount()](#getCount--) | Retourne le nombre de points dans la collection. |
| [get_Item(int index)](#get-Item-int-) | Retourne un point à l'index spécifié. |
| [iterator()](#iterator--) | Retourne un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Retourne un itérateur Java pour l'ensemble de la collection. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Retourne le nombre de points dans la collection. Lecture seule int.

**Retourne :**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Retourne un point à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Retourne :**
[IPoint](../../com.aspose.slides/ipoint) - L'objet [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Retourne un énumérateur qui parcourt la collection.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Retourne un itérateur Java pour l'ensemble de la collection.

**Retourne :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un java.util.Iterator pour l'ensemble de la collection.