---
title: IMotionPath
second_title: Aspose.Slides för Android via Java API-referens
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
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Lägg till ett nytt kommando till sökvägen |
| [getCount()](#getCount--) | Returnerar antalet sökvägar i samlingen. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Infoga ett nytt kommando i sökvägen |
| [clear()](#clear--) | Tar bort alla kommandon från samlingen. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Tar bort specificerade kommandon från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ett kommando på det angivna indexet. |
| [get_Item(int index)](#get-Item-int-) | Returnerar ett kommando på det angivna indexet. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Lägg till ett nytt kommando till sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Typ av kommando för animerad rörelseeffektbeteende [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Punktarray android.graphics.PointF[] |
| ptsType | int | Typ av punkter i animerad rörelsebana [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Anger om relativa koordinater ska användas eller inte boolean |

**Returnerar:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Kommando för en sökväg [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar antalet sökvägar i samlingen. Endast läs int.

**Returnerar:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Infoga ett nytt kommando i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för kommandoinsättning int |
| type | int | Typ av kommando för animerad rörelseeffektbeteende [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Punktarray android.graphics.PointF[] |
| ptsType | int | Typ av punkter i animerad rörelsebana [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
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

Tar bort ett kommando på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för att ta bort kommando int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Returnerar ett kommando på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet. |

**Returnerar:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Kommando på angivet index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)