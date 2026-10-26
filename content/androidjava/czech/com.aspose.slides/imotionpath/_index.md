---
title: IMotionPath
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje dráhu pohybu.
type: docs
url: /cs/com.aspose.slides/imotionpath/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Reprezentuje dráhu pohybu.
## Metody

| Metoda | Popis |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Přidá nový příkaz do cesty |
| [getCount()](#getCount--) | Vrací počet cest ve sbírce. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Vloží nový příkaz do cesty |
| [clear()](#clear--) | Odstraní všechny příkazy ze sbírky. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Odstraní specifikované příkazy ze sbírky. |
| [removeAt(int index)](#removeAt-int-) | Odstraní příkaz na zadaném indexu. |
| [get_Item(int index)](#get-Item-int-) | Vrací příkaz na zadaném indexu. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Přidá nový příkaz do cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | int | Typ příkazu pro chování animačního efektu pohybu [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pole bodů android.graphics.PointF[] |
| ptsType | int | Typ bodů v animační dráze pohybu [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Určuje, zda použít relativní souřadnice, nebo ne boolean |

**Návratová hodnota:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Příkaz cesty [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Vrací počet cest ve sbírce. Pouze pro čtení int.

**Návratová hodnota:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Vloží nový příkaz do cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index pro vložení příkazu int |
| type | int | Typ příkazu pro chování animačního efektu pohybu [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pole bodů android.graphics.PointF[] |
| ptsType | int | Typ bodů v animační dráze pohybu [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Určuje, zda použít relativní souřadnice, nebo ne boolean |
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
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Cesta pohybu k odstranění [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraňuje příkaz na zadaném indexu.

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