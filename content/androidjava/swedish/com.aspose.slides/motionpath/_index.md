---
title: MotionPath
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar rörelsebana.
type: docs
url: /sv/com.aspose.slides/motionpath/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Representerar rörelsebana.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Lägger till nytt kommando i banan |
| [getCount()](#getCount--) | Returnerar antalet banor i samlingen. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Infogar nytt kommando i banan |
| [clear()](#clear--) | Tar bort alla kommandon från samlingen. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Tar bort specificerade kommandon från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ett kommando på det angivna indexet. |
| [get_Item(int index)](#get-Item-int-) | Returnerar ett kommando på det angivna indexet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Lägger till nytt kommando i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array med punkter |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relativa koordinater boolesk |

**Returnerar:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Returnerar antalet banor i samlingen. Skrivskyddad int.

**Returnerar:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Infogar nytt kommando i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade index där objektet ska infogas. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array med punkter |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relativa koordinater boolesk |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla kommandon från samlingen.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Tar bort specificerade kommandon från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Rörelsebana att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort ett kommando på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | |
| index | int | Index för ett kommando som ska raderas. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Returnerar ett kommando på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | |
| index | int | Index för elementet. |

**Returnerar:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)-objektet.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - An java.util.Iterator for the entire collection.