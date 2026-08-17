---
title: PointCollection
second_title: Référence API Aspose.Slides pour Java
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
| [getCount()](#getCount--) | Renvoie le nombre de points de la collection. |
| [get_Item(int index)](#get-Item-int-) | Renvoie un point à l'index spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre de points de la collection. Lecture seule int.

**Retour:** 
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

Renvoie un point à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Retour:** 
[IPoint](../../com.aspose.slides/ipoint) - L'objet [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Retour:** 
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Retour:** 
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un java.util.Iterator pour l'ensemble de la collection.