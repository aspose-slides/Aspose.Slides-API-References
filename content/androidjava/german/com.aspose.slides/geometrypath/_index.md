---
title: GeometryPath
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt den Geometriepfad von GeometryShape dar
type: docs
url: /de/com.aspose.slides/geometrypath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Represents geometry path of GeometryShape
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Erstellt eine Instanz von GeometryPath |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPathData()](#getPathData--) | Gibt den Geometriepfad von GeometryShape als Array von Pfadsegmenten zurück. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Segment am angegebenen Index des Geometriepfads. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Fügt eine Linie am Ende des Pfads hinzu |
| [lineTo(float x, float y)](#lineTo-float-float-) | Fügt eine Linie am Ende des Pfads hinzu |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Fügt eine kubische Bézierkurve am Ende des Pfads hinzu |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Fügt eine kubische Bézierkurve am Ende des Pfads hinzu |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Fügt eine kubische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Fügt eine kubische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu |
| [closeFigure()](#closeFigure--) | Schließt die aktuelle Figur dieses Pfads |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Setzt die Position des nächsten Punktes. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Setzt die Position des nächsten Punktes. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Fügt den angegebenen Bogen zum Pfad hinzu. |
| [getFillMode()](#getFillMode--) | Setzt den Füllmodus |
| [setFillMode(byte value)](#setFillMode-byte-) | Setzt den Füllmodus |
| [getStroke()](#getStroke--) | Setzt das Aussehen des Strichs |
| [setStroke(boolean value)](#setStroke-boolean-) | Setzt das Aussehen des Strichs |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


Erstellt eine Instanz von GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```


Gibt den Geometriepfad von GeometryShape als Array von Pfadsegmenten zurück.

**Rückgabe:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt das Segment am angegebenen Index des Geometriepfads.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu löschenden Segments im Geometriepfad. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```


Fügt eine Linie am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | android.graphics.PointF | Endpunkt der Linie |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```


Fügt eine Linie am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate des Endpunkts der Linie |
| y | float | Y-Koordinate des Endpunkts der Linie |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```


Fügt eine Linie an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | android.graphics.PointF | Endpunkt |
| index | long | Index des Segments in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


Fügt eine Linie an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate des Punktes |
| y | float | Y-Koordinate des Punktes |
| index | long | Index des Segments in PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


Fügt eine kubische Bézierkurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | android.graphics.PointF | Erster Richtpunkt |
| point2 | android.graphics.PointF | Zweiter Richtpunkt |
| point3 | android.graphics.PointF | Endpunkt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Fügt eine kubische Bézierkurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | float | X-Koordinate des ersten Richtpunkts |
| y1 | float | Y-Koordinate des ersten Richtpunkts |
| x2 | float | X-Koordinate des zweiten Richtpunkts |
| y2 | float | Y-Koordinate des zweiten Richtpunkts |
| x3 | float | X-Koordinate des Endpunkts |
| y3 | float | Y-Koordinate des Endpunkts |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


Fügt eine kubische Bézierkurve an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | android.graphics.PointF | Erster Richtpunkt |
| point2 | android.graphics.PointF | Zweiter Richtpunkt |
| point3 | android.graphics.PointF | Endpunkt |
| index | long | Index des Segments in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Fügt eine kubische Bézierkurve an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | float | X-Koordinate des ersten Richtpunkts |
| y1 | float | Y-Koordinate des ersten Richtpunkts |
| x2 | float | X-Koordinate des zweiten Richtpunkts |
| y2 | float | Y-Koordinate des zweiten Richtpunkts |
| x3 | float | X-Koordinate des Endpunkts |
| y3 | float | Y-Koordinate des Endpunkts |
| index | long | Index des Segments in PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```


Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | android.graphics.PointF | Richtpunkt |
| point2 | android.graphics.PointF | Endpunkt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Fügt eine quadratische Bézierkurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | float | X-Koordinate des Richtpunkts |
| y1 | float | Y-Koordinate des Richtpunkts |
| x2 | float | X-Koordinate des Endpunkts |
| y2 | float | Y-Koordinate des Endpunkts |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```


Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | android.graphics.PointF | Richtpunkt |
| point2 | android.graphics.PointF | Endpunkt |
| index | long | Index des Segments in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Fügt eine quadratische Bézierkurve an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | float | X-Koordinate des Richtpunkts |
| y1 | float | Y-Koordinate des Richtpunkts |
| x2 | float | X-Koordinate des Endpunkts |
| y2 | float | Y-Koordinate des Endpunkts |
| index | long | Index des Segments in PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


Schließt die aktuelle Figur dieses Pfads

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```


Setzt die Position des nächsten Punktes.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | android.graphics.PointF | Punktposition |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


Setzt die Position des nächsten Punktes.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate des Punktes |
| y | float | Y-Koordinate des Punktes |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Fügt den angegebenen Bogen zum Pfad hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | float | Breite des Rechtecks |
| heigth | float | Höhe des Rechtecks |
| startAngle | float | Startwinkel |
| sweepAngle | float | Sweep-Winkel/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```


Setzt den Füllmodus

**Rückgabe:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```


Setzt den Füllmodus

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```


Setzt das Aussehen des Strichs

**Rückgabe:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


Setzt das Aussehen des Strichs

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |