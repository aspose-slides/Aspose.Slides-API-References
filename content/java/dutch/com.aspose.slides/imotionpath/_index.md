---
title: IMotionPath
second_title: Aspose.Slides voor Java API Referentie
description: Representeer bewegingspad.
type: docs
url: /nl/com.aspose.slides/imotionpath/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Representeer bewegingspad.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Voeg nieuw commando toe aan pad |
| [getCount()](#getCount--) | Retourneert het aantal paden in de collectie. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Voeg nieuw commando in pad |
| [clear()](#clear--) | Verwijdert alle commando's uit de collectie. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Verwijdert gespecificeerde commando's uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert een commando op de opgegeven index. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een commando op de opgegeven index. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Voeg nieuw commando toe aan pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type van commando voor animatie-bewegingseffectgedrag [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Puntenarray java.awt.geom.Point2D.Float[] |
| ptsType | int | Type van punten in animatie-bewegingspad [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Geeft aan of relatieve coördinaten moeten worden gebruikt boolean |

**Retour:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Commando van een pad [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Retourneert het aantal paden in de collectie. Alleen-lezen int.

**Retour:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Voeg nieuw commando in pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index voor het invoegen van commando int |
| type | int | Type van commando voor animatie-bewegingseffectgedrag [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Puntenarray java.awt.geom.Point2D.Float[] |
| ptsType | int | Type van punten in animatie-bewegingspad [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Geeft aan of relatieve coördinaten moeten worden gebruikt boolean |

### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle commando's uit de collectie.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Verwijdert gespecificeerde commando's uit de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Bewegingspad om te verwijderen [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index voor het verwijderen van commando int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Retourneert een commando op de opgegeven index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van element. |

**Retour:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Commando op opgegeven index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)