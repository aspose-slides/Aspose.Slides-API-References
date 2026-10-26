---
title: MotionPath
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un chemin de mouvement.
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

Représente un chemin de mouvement.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Add new command to path |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Insert new command to path |
| [clear()](#clear--) | Removes all commands from the collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Removes specified commans from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a command at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Returns a command at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |

### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Ajoute une nouvelle commande au chemin

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tableau de points |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booléen indiquant des coordonnées relatives |

**Valeur de retour:**  
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### getCount() {#getCount--}
```
public final int getCount()
```

Returns the number of paths in the collection. Lecture seule int.

**Valeur de retour:**  
int

### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Insert new command to path

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de base zéro auquel l'élément doit être inséré. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Tableau de points |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Booléen indiquant des coordonnées relatives |

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

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Chemin de mouvement à supprimer. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Supprime une commande à l'index spécifié.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la commande à supprimer. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

Renvoie une commande à l'index spécifié.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de l'élément. |

**Valeur de retour:**  
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - The [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) object.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Valeur de retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - un IGenericEnumerator pouvant être utilisé pour parcourir la collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

Renvoie un itérateur Java pour l'ensemble de la collection.

**Valeur de retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - un java.util.Iterator pour l'ensemble de la collection.