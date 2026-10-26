---
title: MotionPath
second_title: Aspose.Slides Androidhoz Java API referencia
description: Mozgási útvonalat ábrázol.
type: docs
url: /hu/com.aspose.slides/motionpath/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Mozgási útvonalat ábrázol.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Új parancs hozzáadása az úthoz |
| [getCount()](#getCount--) | Visszaadja az útvonalak számát a gyűjteményben. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Új parancs beszúrása az úthoz |
| [clear()](#clear--) | Eltávolítja az összes parancsot a gyűjteményből. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Eltávolítja a megadott parancsokat a gyűjteményből. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy parancsot a megadott indexen. |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy parancsot a megadott indexen. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely bejárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy Java iterátort a teljes gyűjteményhez. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Új parancs hozzáadása az úthoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pontok tömbje |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relatív koordináták logikai értéke |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Visszaadja az útvonalak számát a gyűjteményben. Csak olvasható int.

**Visszatérési érték:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Új parancs beszúrása az úthoz

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A 0-alapú index, amelynél az elemet be kell szúrni. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Pontok tömbje |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Relatív koordináták logikai értéke |

### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes parancsot a gyűjteményből.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Eltávolítja a megadott parancsokat a gyűjteményből.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Eltávolítandó mozgási útvonal. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy parancsot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő parancs indexe. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Visszaad egy parancsot a megadott indexen.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatérési érték:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - A [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) objektum.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Visszaad egy enumerátort, amely bejárja a gyűjteményt.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator, amely a gyűjtemény bejárásához használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Visszaad egy Java iterátort a teljes gyűjteményhez.

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Egy java.util.Iterator a teljes gyűjteményhez.