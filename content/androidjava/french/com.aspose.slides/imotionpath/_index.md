---
title: IMotionPath
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le chemin de mouvement.
type: docs
url: /fr/com.aspose.slides/imotionpath/
---
**Toutes les interfaces implémentées :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Représente le chemin de mouvement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Ajoute une nouvelle commande au chemin |
| [getCount()](#getCount--) | Renvoie le nombre de chemins dans la collection. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Insère une nouvelle commande au chemin |
| [clear()](#clear--) | Supprime toutes les commandes de la collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Supprime les commandes spécifiées de la collection. |
| [removeAt(int index)](#removeAt-int-) | Supprime une commande à l'index spécifié. |
| [get_Item(int index)](#get-Item-int-) | Renvoie une commande à l'index spécifié. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Ajoute une nouvelle commande au chemin

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | Type de commande pour le comportement d'effet de mouvement d'animation [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tableau de points android.graphics.PointF[] |
| ptsType | int | Type de points dans le chemin de mouvement d'animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indique s'il faut utiliser des coordonnées relatives ou non boolean |

**Renvoie :**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Commande d'un chemin [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Renvoie le nombre de chemins dans la collection. Lecture seule int.

**Renvoie :**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Insère une nouvelle commande au chemin

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index pour l'insertion de la commande int |
| type | int | Type de commande pour le comportement d'effet de mouvement d'animation [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tableau de points android.graphics.PointF[] |
| ptsType | int | Type de points dans le chemin de mouvement d'animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indique s'il faut utiliser des coordonnées relatives ou non boolean |
### clear() {#clear--}
```
public abstract void clear()
```

Supprime toutes les commandes de la collection.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

Supprime les commandes spécifiées de la collection.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Chemin de mouvement à supprimer [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Supprime une commande à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index pour la suppression de la commande int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Renvoie une commande à l'index spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Renvoie :**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Commande à l'index spécifié [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)