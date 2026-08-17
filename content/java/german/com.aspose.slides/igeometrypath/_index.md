---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Stellt den Geometriepfad von GeometryShape dar
type: docs
url: /de/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Stellt den Geometriepfad von GeometryShape dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPathData()](#getPathData--) | Gibt den Geometriepfad von GeometryShape als Array von Pfadsegmenten zurück. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Segment am angegebenen Index des Geometriepfads. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Fügt eine Linie am Ende des Pfads hinzu |
| [lineTo(float x, float y)](#lineTo-float-float-) | Fügt eine Linie am Ende des Pfads hinzu |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Fügt eine Linie an der angegebenen Stelle des Pfads hinzu |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Fügt eine kubische Bézier-Kurve am Ende des Pfads hinzu |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Fügt eine kubische Bézier-Kurve am Ende des Pfads hinzu |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Fügt eine kubische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Fügt eine kubische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Fügt eine quadratische Bézier-Kurve am Ende des Pfads hinzu |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Fügt eine quadratische Bézier-Kurve am Ende des Pfads hinzu |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Fügt eine quadratische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Fügt eine quadratische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu |
| [closeFigure()](#closeFigure--) | Schließt die aktuelle Figur dieses Pfades |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Setzt die Position des nächsten Punktes. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Setzt die Position des nächsten Punktes. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Fügt den angegebenen Bogen zum Pfad hinzu. |
| [getFillMode()](#getFillMode--) | Setzt den Füllmodus |
| [setFillMode(byte value)](#setFillMode-byte-) | Setzt den Füllmodus |
| [getStroke()](#getStroke--) | Setzt das Aussehen der Kontur |
| [setStroke(boolean value)](#setStroke-boolean-) | Setzt das Aussehen der Kontur |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Gibt den Geometriepfad von GeometryShape als Array von Pfadsegmenten zurück.

**Rückgabe:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt das Segment am angegebenen Index des Geometriepfads.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index des zu löschenden Segments im Geometriepfad. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```


Fügt eine Linie am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Endpunkt der Linie |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Fügt eine Linie am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate des Endpunkts der Linie |
| y | float | Y-Koordinate des Endpunkts der Linie |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```


Fügt eine Linie an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Endpunkt |
| index | long | Index des Segments in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Fügt eine Linie an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate des Punktes |
| y | float | Y-Koordinate des Punktes |
| index | long | Index des Segments in PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Fügt eine kubische Bézier-Kurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Erster Richtpunkt |
| point2 | java.awt.geom.Point2D.Float | Zweiter Richtpunkt |
| point3 | java.awt.geom.Point2D.Float | Endpunkt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Fügt eine kubische Bézier-Kurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | float | X-Koordinate des ersten Richtpunkts |
| y1 | float | Y-Koordinate des ersten Richtpunkts |
| x2 | float | X-Koordinate des zweiten Richtpunkts |
| y2 | float | Y-Koordinate des zweiten Richtpunkts |
| x3 | float | X-Koordinate des Endpunkts |
| y3 | float | Y-Koordinate des Endpunkts |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Fügt eine kubische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Erster Richtpunkt |
| point2 | java.awt.geom.Point2D.Float | Zweiter Richtpunkt |
| point3 | java.awt.geom.Point2D.Float | Endpunkt |
| index | long | Index des Segments in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Fügt eine kubische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu

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

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Fügt eine quadratische Bézier-Kurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Richtpunkt |
| point2 | java.awt.geom.Point2D.Float | Endpunkt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Fügt eine quadratische Bézier-Kurve am Ende des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 | float | X-Koordinate des Richtpunkts |
| y1 | float | Y-Koordinate des Richtpunkts |
| x2 | float | X-Koordinate des Endpunkts |
| y2 | float | Y-Koordinate des Endpunkts |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Fügt eine quadratische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Richtpunkt |
| point2 | java.awt.geom.Point2D.Float | Endpunkt |
| index | long | Index des Segments in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Fügt eine quadratische Bézier-Kurve an der angegebenen Stelle des Pfads hinzu

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
public abstract void closeFigure()
```


Schließt die aktuelle Figur dieses Pfades

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```


Setzt die Position des nächsten Punktes.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Punktposition |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Setzt die Position des nächsten Punktes.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | X-Koordinate des Punktes |
| y | float | Y-Koordinate des Punktes |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Fügt den angegebenen Bogen zum Pfad hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | float | Breite des Rechtecks |
| heigth | float | Höhe des Rechtecks |
| startAngle | float | Startwinkel. |
| sweepAngle | float | Sweep-Winkel/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Setzt den Füllmodus

**Rückgabe:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Setzt den Füllmodus

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Setzt das Aussehen der Kontur

**Rückgabe:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Setzt das Aussehen der Kontur

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |