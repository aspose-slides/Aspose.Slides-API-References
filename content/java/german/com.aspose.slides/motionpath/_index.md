---
title: MotionPath
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Bewegungspfad dar.
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

Stellt einen Bewegungspfad dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Fügt einen neuen Befehl zum Pfad hinzu |
| [getCount()](#getCount--) | Gibt die Anzahl der Pfade in der Sammlung zurück. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Fügt einen neuen Befehl zum Pfad ein |
| [clear()](#clear--) | Entfernt alle Befehle aus der Sammlung. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Entfernt angegebene Befehle aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt einen Befehl am angegebenen Index. |
| [get_Item(int index)](#get-Item-int-) | Gibt einen Befehl am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Fügt einen neuen Befehl zum Pfad hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Array von Punkten |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolescher Wert für relative Koordinaten |

**Rückgabewert:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

Gibt die Anzahl der Pfade in der Sammlung zurück. Nur-Lesen int.

**Rückgabewert:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Fügt einen neuen Befehl zum Pfad ein

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Element eingefügt werden soll. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Array von Punkten |
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

Entfernt einen Befehl am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Befehls, der gelöscht werden soll. |
### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

Gibt einen Befehl am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des Elements. |

**Rückgabewert:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Das [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) Objekt.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Ein IGenericEnumerator, der verwendet werden kann, um die Sammlung zu durchlaufen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Ein java.util.Iterator für die gesamte Sammlung.