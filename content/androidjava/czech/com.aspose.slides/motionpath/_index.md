---
title: MotionPath
second_title: Aspose.Slides pro Android přes Java API
description: Reprezentuje cestu pohybu.
type: docs
url: /cs/com.aspose.slides/motionpath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Reprezentuje cestu pohybu.
## Konstruktory

| Constructor | Popis |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Metody

| Method | Popis |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Přidá nový příkaz do cesty |
| [getCount()](#getCount--) | Vrací počet cest ve sbírce. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Vloží nový příkaz do cesty |
| [clear()](#clear--) | Odstraní všechny příkazy ze sbírky. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Odstraní zadané příkazy ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraní příkaz na zadaném indexu. |
| [get_Item(int index)](#get-Item-int-) | Vrací příkaz na zadaném indexu. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází sbírku. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou sbírku. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Přidá nový příkaz do cesty

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pole bodů |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolovská hodnota relativních souřadnic |

**Vrací:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet cest ve sbírce. Pouze pro čtení int.

**Vrací:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Vloží nový příkaz do cesty

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Nulový index, na který má být položka vložena. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pole bodů |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolovská hodnota relativních souřadnic |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny příkazy ze sbírky.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Odstraní zadané příkazy ze sbírky.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Cesta pohybu k odstranění. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní příkaz na zadaném indexu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index příkazu, který má být smazán. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Vrací příkaz na zadaném indexu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index prvku. |

**Vrací:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) objekt.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Vrací enumerátor, který prochází sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - IGenericEnumerator, který lze použít k iteraci přes sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Vrací java iterátor pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java.util.Iterator pro celou sbírku.