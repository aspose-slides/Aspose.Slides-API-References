---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Stelt het geometrische pad van GeometryShape voor
type: docs
url: /nl/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Stelt het geometrische pad van GeometryShape voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPathData()](#getPathData--) | Retourneert het geometrische pad van GeometryShape als een array van padsegmenten. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert segment op de opgegeven index van het geometrische pad. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Voegt een lijn toe aan het einde van het pad |
| [lineTo(float x, float y)](#lineTo-float-float-) | Voegt een lijn toe aan het einde van het pad |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad |
| [closeFigure()](#closeFigure--) | Sluit de huidige figuur van dit pad |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Stelt de positie van het volgende punt in. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Stelt de positie van het volgende punt in. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Voegt de opgegeven boog toe aan het pad. |
| [getFillMode()](#getFillMode--) | Stelt de vulmodus in |
| [setFillMode(byte value)](#setFillMode-byte-) | Stelt de vulmodus in |
| [getStroke()](#getStroke--) | Stelt de stroke-weergave in |
| [setStroke(boolean value)](#setStroke-boolean-) | Stelt de stroke-weergave in |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Retourneert het geometrische pad van GeometryShape als een array van padsegmenten.

**Retour:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Verwijdert segment op de opgegeven index van het geometrische pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het geometrische pad dat moet worden verwijderd. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```


Voegt een lijn toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Eindpunt van de lijn |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Voegt een lijn toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van het eindpunt van de lijn |
| y | float | Y-coördinaat van het eindpunt van de lijn |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```


Voegt een lijn toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Eindpunt |
| index | long | Index van segment in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Voegt een lijn toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van het punt |
| y | float | Y-coördinaat van het punt |
| index | long | Index van segment in PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Voegt een kubieke Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Eerste richtingspunt |
| point2 | java.awt.geom.Point2D.Float | Tweede richtingspunt |
| point3 | java.awt.geom.Point2D.Float | Eindpunt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Voegt een kubieke Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x1 | float | X-coördinaat van het eerste richtingspunt |
| y1 | float | Y-coördinaat van het eerste richtingspunt |
| x2 | float | X-coördinaat van het tweede richtingspunt |
| y2 | float | Y-coördinaat van het tweede richtingspunt |
| x3 | float | X-coördinaat van het eindpunt |
| y3 | float | Y-coördinaat van het eindpunt |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Eerste richtingspunt |
| point2 | java.awt.geom.Point2D.Float | Tweede richtingspunt |
| point3 | java.awt.geom.Point2D.Float | Eindpunt |
| index | long | Index van segment in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x1 | float | X-coördinaat van het eerste richtingspunt |
| y1 | float | Y-coördinaat van het eerste richtingspunt |
| x2 | float | X-coördinaat van het tweede richtingspunt |
| y2 | float | Y-coördinaat van het tweede richtingspunt |
| x3 | float | X-coördinaat van het eindpunt |
| y3 | float | Y-coördinaat van het eindpunt |
| index | long | Index van segment in PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Voegt een kwadratische Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Richtingspunt |
| point2 | java.awt.geom.Point2D.Float | Eindpunt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Voegt een kwadratische Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x1 | float | X-coördinaat van het richtingspunt |
| y1 | float | Y-coördinaat van het richtingspunt |
| x2 | float | X-coördinaat van het eindpunt |
| y2 | float | Y-coördinaat van het eindpunt |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Richtingspunt |
| point2 | java.awt.geom.Point2D.Float | Eindpunt |
| index | long | Index van segment in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x1 | float | X-coördinaat van het richtingspunt |
| y1 | float | Y-coördinaat van het richtingspunt |
| x2 | float | X-coördinaat van het eindpunt |
| y2 | float | Y-coördinaat van het eindpunt |
| index | long | Index van segment in PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


Sluit de huidige figuur van dit pad

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```


Stelt de positie van het volgende punt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Puntpositie |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Stelt de positie van het volgende punt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van het punt |
| y | float | Y-coördinaat van het punt |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Voegt de opgegeven boog toe aan het pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | float | Breedte van de rechthoek |
| heigth | float | Hoogte van de rechthoek |
| startAngle | float | Beginhoek. |
| sweepAngle | float | Sweep angle/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Stelt de vulmodus in

**Retour:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Stelt de vulmodus in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Stelt de stroke-weergave in

**Retour:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Stelt de stroke-weergave in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |