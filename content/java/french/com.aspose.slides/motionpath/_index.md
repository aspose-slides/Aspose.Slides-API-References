---
title: MotionPath
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente le chemin de mouvement.
type: docs
url: /fr/com.aspose.slides/motionpath/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Représente le chemin de mouvement.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Ajoute une nouvelle commande au chemin |
| [getCount()](#getCount--) | Renvoie le nombre de chemins dans la collection. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Insère une nouvelle commande au chemin |
| [clear()](#clear--) | Supprime toutes les commandes de la collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Supprime les commandes spécifiées de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime une commande à l'index spécifié. |
| [get_Item(int index)](#get-Item-int-) | Renvoie une commande à l'index spécifié. |
| [iterator()](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [iteratorJava()](#iteratorJava--) | Renvoie un itérateur java pour l'ensemble de la collection. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Ajoute une nouvelle commande au chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Tableau de points |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booléen de coordonnées relatives |

**Renvoie :**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

Renvoie le nombre de chemins dans la collection. int en lecture seule.

**Renvoie :**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Insère une nouvelle commande au chemin

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro à lequel l'élément doit être inséré. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Tableau de points |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booléen de coordonnées relatives |
### clear() {#clear--}
```
public final void clear()
```

Supprime toutes les commandes de la collection.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

Supprime les commandes spécifiées de la collection.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Chemin de mouvement à supprimer. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime une commande à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index d'une commande qui doit être supprimée. |
### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

Renvoie une commande à l'index spécifié.

**Paramètre :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |
**Renvoie :**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - L'objet [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Un IGenericEnumerator qui peut être utilisé pour parcourir la collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

Renvoie un itérateur java pour l'ensemble de la collection.

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Un java.util.Iterator pour l'ensemble de la collection.