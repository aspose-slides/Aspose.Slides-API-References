---
title: GeometryPath
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt geometrisch pad van GeometryShape
type: docs
url: /nl/com.aspose.slides/geometrypath/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Vertegenwoordigt geometrisch pad van GeometryShape
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Maakt een instantie van GeometryPath |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPathData()](#getPathData--) | Retourneert geometrisch pad van GeometryShape als een array van padsegmenten. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert segment op de opgegeven index van het geometrische pad. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Voegt een lijn toe aan het einde van het pad |
| [lineTo(float x, float y)](#lineTo-float-float-) | Voegt een lijn toe aan het einde van het pad |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Voegt een lijn toe op de opgegeven plaats van het pad |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad |
| [closeFigure()](#closeFigure--) | Sluit de huidige figuur van dit pad |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Stelt de positie van het volgende punt in. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Stelt de positie van het volgende punt in. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Voegt de opgegeven boog toe aan het pad. |
| [getFillMode()](#getFillMode--) | Stelt vulmodus in |
| [setFillMode(byte value)](#setFillMode-byte-) | Stelt vulmodus in |
| [getStroke()](#getStroke--) | Stelt stroke-weergave in |
| [setStroke(boolean value)](#setStroke-boolean-) | Stelt stroke-weergave in |
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

**Retour:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert segment op de opgegeven index van het geometrische pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het geometrische pad dat verwijderd moet worden. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Voegt een lijn toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | android.graphics.PointF | Eindpunt van de lijn |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Voegt een lijn toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van het eindpunt van de lijn |
| y | float | Y-coördinaat van het eindpunt van de lijn |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Voegt een lijn toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | android.graphics.PointF | Eindpunt |
| index | long | Index van segment in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Voegt een lijn toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van het punt |
| y | float | Y-coördinaat van het punt |
| index | long | Index van segment in PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Voegt een kubieke Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | android.graphics.PointF | Eerste richtpunt |
| point2 | android.graphics.PointF | Tweede richtpunt |
| point3 | android.graphics.PointF | Eindpunt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Voegt een kubieke Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x1 | float | X-coördinaat van het eerste richtpunt |
| y1 | float | Y-coördinaat van het eerste richtpunt |
| x2 | float | X-coördinaat van het tweede richtpunt |
| y2 | float | Y-coördinaat van het tweede richtpunt |
| x3 | float | X-coördinaat van het eindpunt |
| y3 | float | Y-coördinaat van het eindpunt |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | android.graphics.PointF | Eerste richtpunt |
| point2 | android.graphics.PointF | Tweede richtpunt |
| point3 | android.graphics.PointF | Eindpunt |
| index | long | Index van segment in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x1 | float | X-coördinaat van het eerste richtpunt |
| y1 | float | Y-coördinaat van het eerste richtpunt |
| x2 | float | X-coördinaat van het tweede richtpunt |
| y2 | float | Y-coördinaat van het tweede richtpunt |
| x3 | float | X-coördinaat van het eindpunt |
| y3 | float | Y-coördinaat van het eindpunt |
| index | long | Index van segment in PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Voegt een kwadratische Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | android.graphics.PointF | Richtpunt |
| point2 | android.graphics.PointF | Eindpunt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Voegt een kwadratische Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x1 | float | X-coördinaat van het richtpunt |
| y1 | float | Y-coördinaat van het richtpunt |
| x2 | float | X-coördinaat van het eindpunt |
| y2 | float | Y-coördinaat van het eindpunt |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | android.graphics.PointF | Richtpunt |
| point2 | android.graphics.PointF | Eindpunt |
| index | long | Index van segment in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
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

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Stelt de positie van het volgende punt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | android.graphics.PointF | Puntpositie |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Stelt de positie van het volgende punt in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van het punt |
| y | float | Y-coördinaat van het punt |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Voegt de opgegeven boog toe aan het pad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | float | Breedte van het rechthoek |
| heigth | float | Hoogte van het rechthoek |
| startAngle | float | Starthoek. |
| sweepAngle | float | Sweep angle/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Stelt vulmodus in

**Retour:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Stelt vulmodus in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Stelt stroke-weergave in

**Retour:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Stelt stroke-weergave in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |