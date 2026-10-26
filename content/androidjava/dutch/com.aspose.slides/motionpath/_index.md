---
title: MotionPath
second_title: Aspose.Slides voor Android via Java API-referentie
description: Geeft een bewegingspad weer.
type: docs
url: /nl/com.aspose.slides/motionpath/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Geeft een bewegingspad weer.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Voegt een nieuw commando toe aan het pad |
| [getCount()](#getCount--) | Retourneert het aantal paden in de collectie. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Insert new command to path |
| [clear()](#clear--) | Verwijdert alle commando's uit de collectie. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Verwijdert gespecificeerde commando's uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een commando op de opgegeven index. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een commando op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Voegt een nieuw commando toe aan het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array van punten |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolean voor relatieve coördinaten |

**Retourwaarde:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Retourneert het aantal paden in de collectie. Alleen-lezen int.

**Retourwaarde:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Insert new command to path

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop het item moet worden ingevoegd. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array van punten |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolean voor relatieve coördinaten |

### clear() {#clear--}
```
public final void clear()
```


Verwijdert alle commando's uit de collectie.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Verwijdert gespecificeerde commando's uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Bewegingspad om te verwijderen. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een commando dat moet worden verwijderd. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Retourneert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retourwaarde:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - De [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Retourneert een enumerator die door de collectie itereert.

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Retourneert een java-iterator voor de volledige collectie.

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Een java.util.Iterator voor de volledige collectie.