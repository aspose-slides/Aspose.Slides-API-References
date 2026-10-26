---
title: IMotionPath
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje dráhu pohybu.
type: docs
url: /cs/com.aspose.slides/imotionpath/
---
**Všechna implementovaná rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Reprezentuje dráhu pohybu.
## Metody

| Metoda | Popis |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Přidá nový příkaz do cesty |
| [getCount()](#getCount--) | Vrací počet cest ve sbírce. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Vloží nový příkaz do cesty |
| [clear()](#clear--) | Odstraní všechny příkazy ze sbírky. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Odstraní specifikované příkazy ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraní příkaz na zadaném indexu. |
| [get_Item(int index)](#get-Item-int-) | Vrací příkaz na zadaném indexu. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Přidá nový příkaz do cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ příkazu pro animaci pohybového efektu [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pole bodů java.awt.geom.Point2D.Float[] |
| ptsType | int | Typ bodů v animované dráze pohybu [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Určuje, zda použít relativní souřadnice nebo ne boolean |

**Návratová hodnota:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Příkaz cesty [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Vrací počet cest ve sbírce. Pouze pro čtení int.

**Návratová hodnota:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Vloží nový příkaz do cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index pro vložení příkazu int |
| type | int | Typ příkazu pro animaci pohybového efektu [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pole bodů java.awt.geom.Point2D.Float[] |
| ptsType | int | Typ bodů v animované dráze pohybu [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Určuje, zda použít relativní souřadnice nebo ne boolean |

### clear() {#clear--}
```
public abstract void clear()
```


Odstraní všechny příkazy ze sbírky.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Odstraní specifikované příkazy ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Dráha pohybu k odstranění [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní příkaz na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index pro odstranění příkazu int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Vrací příkaz na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku. |

**Návratová hodnota:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Příkaz na zadaném indexu [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)