---
title: IMotionPath
second_title: Aspose.Slides för Java API-referens
description: Representerar rörelsebana.
type: docs
url: /sv/com.aspose.slides/imotionpath/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Representerar rörelsebana.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Lägg till nytt kommando till banan |
| [getCount()](#getCount--) | Returnerar antalet banor i samlingen. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Infoga nytt kommando till banan |
| [clear()](#clear--) | Tar bort alla kommandon från samlingen. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Tar bort specificerade kommandon från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ett kommando på angivet index. |
| [get_Item(int index)](#get-Item-int-) | Returnerar ett kommando på angivet index. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Lägg till nytt kommando till banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Typ av kommando för animeringsrörelseeffektbeteende [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Punktarray java.awt.geom.Point2D.Float[] |
| ptsType | int | Typ av punkter i animeringsrörelsebana [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Anger om relativa koordinater ska användas eller inte boolean |

**Returnerar:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Kommando för en bana [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar antalet banor i samlingen. Read-only int.

**Returnerar:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Infoga nytt kommando till banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för kommandoinsättning int |
| type | int | Typ av kommando för animeringsrörelseeffektbeteende [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Punktarray java.awt.geom.Point2D.Float[] |
| ptsType | int | Typ av punkter i animeringsrörelsebana [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Anger om relativa koordinater ska användas eller inte boolean |
### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla kommandon från samlingen.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

Tar bort specificerade kommandon från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Rörelsebana att ta bort [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort ett kommando på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för att ta bort kommando int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Returnerar ett kommando på angivet index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet. |
**Returnerar:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Kommando på specificerat index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)