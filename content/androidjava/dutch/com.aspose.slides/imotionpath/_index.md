---
title: IMotionPath
second_title: Aspose.Slides voor Android via Java API-referentie
description: Beeld het bewegingspad weer.
type: docs
url: /nl/com.aspose.slides/imotionpath/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Beeld het bewegingspad weer.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Voeg een nieuw commando toe aan het pad |
| [getCount()](#getCount--) | Retourneert het aantal paden in de collectie. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Voeg een nieuw commando in het pad toe |
| [clear()](#clear--) | Verwijdert alle commando's uit de verzameling. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Verwijdert opgegeven commando's uit de verzameling. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een commando op de opgegeven index. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een commando op de opgegeven index. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Voeg een nieuw commando toe aan het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Type van commando voor animatiebewegingseffectgedrag [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Puntenarray android.graphics.PointF[] |
| ptsType | int | Type van punten in animatiebewegingspad [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Geeft aan of relatieve coördinaten gebruikt moeten worden of niet boolean |

**Retourwaarde:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Commando van een pad [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Retourneert het aantal paden in de collectie. Alleen-lezen int.

**Retourwaarde:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Voeg een nieuw commando in het pad toe

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index voor het invoegen van het commando int |
| type | int | Type van commando voor animatiebewegingseffectgedrag [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Puntenarray android.graphics.PointF[] |
| ptsType | int | Type van punten in animatiebewegingspad [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Geeft aan of relatieve coördinaten gebruikt moeten worden of niet boolean |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle commando's uit de verzameling.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

Verwijdert opgegeven commando's uit de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Te verwijderen bewegingspad [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index voor het verwijderen van het commando int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Retourneert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retourwaarde:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Commando op opgegeven index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)