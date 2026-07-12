---
title: IMotionPath
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt den Bewegungspfad dar.
type: docs
url: /de/com.aspose.slides/imotionpath/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath)
```

Stellt den Bewegungspfad dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Fügt einen neuen Befehl zum Pfad hinzu. |
| [getCount()](#getCount--) | Gibt die Anzahl der Pfade in der Sammlung zurück. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Fügt einen neuen Befehl in den Pfad ein. |
| [clear()](#clear--) | Entfernt alle Befehle aus der Sammlung. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Entfernt angegebene Befehle aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Befehl am angegebenen Index. |
| [get_Item(int index)](#get-Item-int-) | Gibt einen Befehl am angegebenen Index zurück. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Fügt einen neuen Befehl zum Pfad hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Typ des Befehls für das Animationsbewegungseffektverhalten [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Punkte-Array android.graphics.PointF[] |
| ptsType | int | Typ der Punkte im Animationsbewegungspfad [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Gibt an, ob relative Koordinaten verwendet werden sollen oder nicht boolean |

**Rückgabewert:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Befehl eines Pfads [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Gibt die Anzahl der Pfade in der Sammlung zurück. Nur-Lese int.

**Rückgabewert:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Fügt einen neuen Befehl in den Pfad ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index für das Einfügen des Befehls int |
| type | int | Typ des Befehls für das Animationsbewegungseffektverhalten [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Punkte-Array android.graphics.PointF[] |
| ptsType | int | Typ der Punkte im Animationsbewegungspfad [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Gibt an, ob relative Koordinaten verwendet werden sollen oder nicht boolean |
### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Befehle aus der Sammlung.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

Entfernt angegebene Befehle aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Bewegungspfad zum Entfernen [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt einen Befehl am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index zum Entfernen des Befehls int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Gibt einen Befehl am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabewert:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Befehl am angegebenen Index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)