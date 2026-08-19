---
title: MotionPath
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje dráhu pohybu.
type: docs
url: /cs/com.aspose.slides/motionpath/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Reprezentuje motion path.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Přidá nový příkaz do cesty |
| [getCount()](#getCount--) | Vrací počet cest ve sbírce. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Vloží nový příkaz do cesty |
| [clear()](#clear--) | Odstraní všechny příkazy ze sbírky. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Odstraní specifikované příkazy ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraní příkaz na zadaném indexu. |
| [get_Item(int index)](#get-Item-int-) | Vrátí příkaz na zadaném indexu. |
| [iterator()](#iterator--) | Vrátí enumerátor, který prochází sbírku. |
| [iteratorJava()](#iteratorJava--) | Vrátí java iterátor pro celou sbírku. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Přidá nový příkaz do cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pole bodů |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Logická hodnota relativních souřadnic |

**Návratová hodnota:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Vrací počet cest ve sbírce. Pouze pro čtení int.

**Návratová hodnota:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Vloží nový příkaz do cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index založený na nule, kam má být položka vložena. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pole bodů |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Logická hodnota relativních souřadnic |

### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny příkazy ze sbírky.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Odstraní specifikované příkazy ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Motion path, který má být odstraněn. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní příkaz na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index příkazu, který má být smazán. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Vrátí příkaz na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index elementu. |

**Návratová hodnota:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Objekt [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Vrátí enumerátor, který prochází sbírku.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - IGenericEnumerator, který lze použít k iteraci přes sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Vrátí java iterátor pro celou sbírku.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java/util/Iterator pro celou sbírku.