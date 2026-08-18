---
title: MotionPath
second_title: Aspose.Slides for Java API Referenciája
description: Mozgásútvonalat képvisel.
type: docs
url: /hu/com.aspose.slides/motionpath/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Mozgásútvonalat képvisel.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Új parancs hozzáadása az útvonalhoz |
| [getCount()](#getCount--) | Visszaadja az útvonalak számát a gyűjteményben. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Új parancs beszúrása az útvonalba |
| [clear()](#clear--) | Az összes parancs eltávolítása a gyűjteményből. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | A megadott parancsok eltávolítása a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Parancs eltávolítása a megadott indexnél. |
| [get_Item(int index)](#get-Item-int-) | Parancs visszaadása a megadott indexnél. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort az egész gyűjteményhez. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Új parancs hozzáadása az útvonalhoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pontok tömbje |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relatív koordináták logikai értéke |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Visszaadja az útvonalak számát a gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Új parancs beszúrása az útvonalba

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A nulla-alapú index, ahová az elem beillesztésre kerül. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pontok tömbje |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relatív koordináták logikai értéke |

### clear() {#clear--}
```
public final void clear()
```


Az összes parancs eltávolítása a gyűjteményből.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


A megadott parancsok eltávolítása a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Az eltávolítandó mozgásútvonal. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Parancs eltávolítása a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő parancs indexe. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Parancs visszaadása a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - A [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) objektum.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Egy IGenericEnumerator, amelyet a gyűjtemény bejárására lehet használni.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Visszaad egy Java iterátort az egész gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Egy java.util.Iterator az egész gyűjteményhez.