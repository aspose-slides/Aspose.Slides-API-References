---
title: MotionPath
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt Bewegungspfad dar.
type: docs
url: /de/com.aspose.slides/motionpath/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Stellt Bewegungspfad dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Fügt einen neuen Befehl zum Pfad hinzu |
| [getCount()](#getCount--) | Gibt die Anzahl der Pfade in der Sammlung zurück. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Fügt einen neuen Befehl in den Pfad ein |
| [clear()](#clear--) | Entfernt alle Befehle aus der Sammlung. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Entfernt angegebene Befehle aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt ein Befehl am angegebenen Index. |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Kommando am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Fügt einen neuen Befehl zum Pfad hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array von Punkten |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolescher Wert für relative Koordinaten |

**Rückgabe:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der Pfade in der Sammlung zurück. Nur-Lese int.

**Rückgabe:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Fügt einen neuen Befehl in den Pfad ein

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Nullbasierter Index, an dem das Element eingefügt werden soll. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array von Punkten |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolescher Wert für relative Koordinaten |
### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Befehle aus der Sammlung.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

Entfernt angegebene Befehle aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Zu entfernender Bewegungspfad. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt ein Befehl am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Befehls, der gelöscht werden soll. |
### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

Gibt ein Kommando am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabe:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Das [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) Objekt.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Ein java.util.Iterator für die gesamte Sammlung.