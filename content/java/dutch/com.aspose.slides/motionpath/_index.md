---
title: MotionPath
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een bewegingspad voor.
type: docs
url: /nl/com.aspose.slides/motionpath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Stelt een bewegingspad voor.
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Methoden

| Method | Beschrijving |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Voeg een nieuw commando toe aan het pad |
| [getCount()](#getCount--) | Retourneert het aantal paden in de collectie. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Voeg een nieuw commando toe aan het pad |
| [clear()](#clear--) | Verwijdert alle commando's uit de collectie. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Verwijdert opgegeven commando's uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een commando op de opgegeven index. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een commando op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Voeg een nieuw commando toe aan het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Array van punten |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolse relatieve coördinaten |

**Retour:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Retourneert het aantal paden in de collectie. Alleen-lezen int.

**Retour:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Voeg een nieuw commando toe aan het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index waarop het item moet worden ingevoegd. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Array van punten |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolse relatieve coördinaten |

### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle commando's uit de collectie.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Verwijdert opgegeven commando's uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Te verwijderen bewegingspad. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het commando dat moet worden verwijderd. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Retourneert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retour:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Het [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Retourneert een enumerator die door de collectie iterereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Een IGenericEnumerator die gebruikt kan worden om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Een java.util.Iterator voor de volledige collectie.