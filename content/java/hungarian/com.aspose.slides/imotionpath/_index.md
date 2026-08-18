---
title: IMotionPath
second_title: Aspose.Slides for Java API referenciája
description: Mozgáspálya ábrázolása.
type: docs
url: /hu/com.aspose.slides/imotionpath/
---
**Minden implementált interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Mozgáspálya ábrázolása.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Új parancs hozzáadása az útvonalhoz |
| [getCount()](#getCount--) | Visszaadja az útvonalak számát a gyűjteményben. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Új parancs beszúrása az útvonalhoz |
| [clear()](#clear--) | Eltávolítja az összes parancsot a gyűjteményből. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Eltávolítja a megadott parancsokat a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy parancsot a megadott indexen. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy parancsot a megadott indexen. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Új parancs hozzáadása az útvonalhoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A parancs típusa az animációs mozgáseffektus viselkedéséhez [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pontok tömbje java.awt.geom.Point2D.Float[] |
| ptsType | int | A pontok típusa az animációs mozgáspályán [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Jelzi, hogy relatív koordinátákat kell-e használni vagy sem boolean |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Az útvonal parancsa [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Visszaadja az útvonalak számát a gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Új parancs beszúrása az útvonalhoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a parancs beszúrásához |
| type | int | A parancs típusa az animációs mozgáseffektus viselkedéséhez [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Pontok tömbje java.awt.geom.Point2D.Float[] |
| ptsType | int | A pontok típusa az animációs mozgáspályán [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Jelzi, hogy relatív koordinátákat kell-e használni vagy sem boolean |
### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes parancsot a gyűjteményből.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

Eltávolítja a megadott parancsokat a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Eltávolítandó mozgáspálya [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy parancsot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az index a parancs eltávolításához |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Visszaad egy parancsot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Parancs a megadott indexen [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)