---
title: GeometryPath
second_title: Aspose.Slides voor Java API Referentie
description: Stelt het geometrische pad van GeometryShape voor
type: docs
url: /nl/com.aspose.slides/geometrypath/
---
**Erfelijkheid:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Stelt de geometrische pad van GeometryShape voor
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Maakt een instantie van GeometryPath |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getPathData()](#getPathData--) | Retourneert geometrisch pad van GeometryShape als een array van padsegmenten. |
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
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Stelt de volgende puntpositie in. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Stelt de volgende puntpositie in. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Voegt de opgegeven boog toe aan het pad. |
| [getFillMode()](#getFillMode--) | Stelt vulmodus in |
| [setFillMode(byte value)](#setFillMode-byte-) | Stelt vulmodus in |
| [getStroke()](#getStroke--) | Stelt de lijnstijl in |
| [setStroke(boolean value)](#setStroke-boolean-) | Stelt de lijnstijl in |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


Maakt een instantie van GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```


Retourneert geometrisch pad van GeometryShape als een array van padsegmenten.

**Returns:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Verwijdert segment op de opgegeven index van het geometrische pad.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van het geometrische pad dat moet worden verwijderd. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```


Voegt een lijn toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Eindpunt van de lijn |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```


Voegt een lijn toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X-coördinaat van het eindpunt van de lijn |
| y | float | Y-coördinaat van het eindpunt van de lijn |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```


Voegt een lijn toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Eindpunt |
| index | long | Index van segment in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


Voegt een lijn toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X-coördinaat van het punt |
| y | float | Y-coördinaat van het punt |
| index | long | Index van segment in PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Voegt een kubieke Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Eerste richtpunt |
| point2 | java.awt.geom.Point2D.Float | Tweede richtpunt |
| point3 | java.awt.geom.Point2D.Float | Eindpunt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Voegt een kubieke Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X-coördinaat van het eerste richtpunt |
| y1 | float | Y-coördinaat van het eerste richtpunt |
| x2 | float | X-coördinaat van het tweede richtpunt |
| y2 | float | Y-coördinaat van het tweede richtpunt |
| x3 | float | X-coördinaat van het eindpunt |
| y3 | float | Y-coördinaat van het eindpunt |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Eerste richtpunt |
| point2 | java.awt.geom.Point2D.Float | Tweede richtpunt |
| point3 | java.awt.geom.Point2D.Float | Eindpunt |
| index | long | Index van segment in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X-coördinaat van het eerste richtpunt |
| y1 | float | Y-coördinaat van het eerste richtpunt |
| x2 | float | X-coördinaat van het tweede richtpunt |
| y2 | float | Y-coördinaat van het tweede richtpunt |
| x3 | float | X-coördinaat van het eindpunt |
| y3 | float | Y-coördinaat van het eindpunt |
| index | long | Index van segment in PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Voegt een kwadratische Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Richtpunt |
| point2 | java.awt.geom.Point2D.Float | Eindpunt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Voegt een kwadratische Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X-coördinaat van het richtpunt |
| y1 | float | Y-coördinaat van het richtpunt |
| x2 | float | X-coördinaat van het eindpunt |
| y2 | float | Y-coördinaat van het eindpunt |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Richtpunt |
| point2 | java.awt.geom.Point2D.Float | Eindpunt |
| index | long | Index van segment in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | X-coördinaat van het richtpunt |
| y1 | float | Y-coördinaat van het richtpunt |
| x2 | float | X-coördinaat van het eindpunt |
| y2 | float | Y-coördinaat van het eindpunt |
| index | long | Index van segment in PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


Sluit de huidige figuur van dit pad

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```


Stelt de volgende puntpositie in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Positie van het punt |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


Stelt de volgende puntpositie in.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | X-coördinaat van het punt |
| y | float | Y-coördinaat van het punt |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Voegt de opgegeven boog toe aan het pad.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Breedte van de rechthoek |
| heigth | float | Hoogte van de rechthoek |
| startAngle | float | Starthoek. |
| sweepAngle | float | Sweep angle/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```


Stelt vulmodus in

**Returns:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```


Stelt vulmodus in

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```


Stelt de lijnstijl in

**Returns:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


Stelt de lijnstijl in

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |