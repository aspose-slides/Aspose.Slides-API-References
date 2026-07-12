---
title: IMotionPath
second_title: Aspose.Slides for Android Java API-referencia
description: Mozgáspálya reprezentálása.
type: docs
url: /hu/com.aspose.slides/imotionpath/
---
**Az összes megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Mozgáspálya reprezentálása.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Új parancs hozzáadása az úthoz |
| [getCount()](#getCount--) | Visszaadja az útvonalak számát a gyűjteményben. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Új parancs beszúrása az úthoz |
| [clear()](#clear--) | Eltávolítja az összes parancsot a gyűjteményből. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Eltávolítja a megadott parancsokat a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a parancsot a megadott indexen. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy parancsot a megadott indexen. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Új parancs hozzáadása az úthoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | A parancs típusa az animációs mozgáshatást viselkedéshez [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pontok tömbje android.graphics.PointF[] |
| ptsType | int | A pontok típusa az animációs mozgáspályában [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Megadja, hogy relatív koordinátákat kell-e használni vagy sem, boolean |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command of a path [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Visszaadja az útvonalak számát a gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Új parancs beszúrása az úthoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index a parancs beszúrásához int |
| type | int | A parancs típusa az animációs mozgáshatást viselkedéshez [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pontok tömbje android.graphics.PointF[] |
| ptsType | int | A pontok típusa az animációs mozgáspályában [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Megadja, hogy relatív koordinátákat kell-e használni vagy sem, boolean |

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


Eltávolítja a parancsot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index a parancs eltávolításához int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Visszaad egy parancsot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Elem indexe. |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command at specified index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)