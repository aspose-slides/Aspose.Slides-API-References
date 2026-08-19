---
title: GeometryPath
second_title: Aspose.Slides för Java API-referens
description: Representerar geometrisk bana för GeometryShape
type: docs
url: /sv/com.aspose.slides/geometrypath/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Representerar geometrisk bana för GeometryShape
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Skapar en instans av GeometryPath |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPathData()](#getPathData--) | Returnerar geometrisk bana för GeometryShape som en array av bansegment. |
| [removeAt(int index)](#removeAt-int-) | Tar bort segmentet på det angivna indexet i den geometriska banan. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Lägger till en linje i slutet av banan |
| [lineTo(float x, float y)](#lineTo-float-float-) | Lägger till en linje i slutet av banan |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Lägger till en linje på den angivna platsen i banan |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Lägger till en linje på den angivna platsen i banan |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Lägger till en kubisk Bezier-kurva i slutet av banan |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Lägger till en kubisk Bezier-kurva i slutet av banan |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Lägger till en kubisk Bezier-kurva på den angivna platsen i banan |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Lägger till en kubisk Bezier-kurva på den angivna platsen i banan |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Lägger till en kvadratisk Bezier-kurva i slutet av banan |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Lägger till en kvadratisk Bezier-kurva i slutet av banan |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Lägger till en kvadratisk Bezier-kurva på den angivna platsen i banan |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Lägger till en kvadratisk Bezier-kurva på den angivna platsen i banan |
| [closeFigure()](#closeFigure--) | Stänger den aktuella figuren i denna bana |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Ställer in nästa punkts position. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ställer in nästa punkts position. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Lägger till den angivna bågen till banan. |
| [getFillMode()](#getFillMode--) | Ställer in fyllningsläge |
| [setFillMode(byte value)](#setFillMode-byte-) | Ställer in fyllningsläge |
| [getStroke()](#getStroke--) | Ställer in penselns utseende |
| [setStroke(boolean value)](#setStroke-boolean-) | Ställer in penselns utseende |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Skapar en instans av GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Returnerar geometrisk bana för GeometryShape som en array av bansegment.

**Returnerar:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort segmentet på det angivna indexet i den geometriska banan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den geometriska banan som ska tas bort. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

Lägger till en linje i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Slutpunkt för linjen |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Lägger till en linje i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för linjens slutpunkt |
| y | float | Y-koordinat för linjens slutpunkt |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

Lägger till en linje på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Slutpunkt |
| index | long | Index för segment i PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Lägger till en linje på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |
| index | long | Index för segment i PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Lägger till en kubisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Första riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Andra riktningspunkt |
| point3 | java.awt.geom.Point2D.Float | Slutpunkt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Lägger till en kubisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkten |
| y1 | float | Y-koordinat för första riktningspunkten |
| x2 | float | X-koordinat för andra riktningspunkten |
| y2 | float | Y-koordinat för andra riktningspunkten |
| x3 | float | X-koordinat för slutpunkten |
| y3 | float | Y-koordinat för slutpunkten |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Lägger till en kubisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Första riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Andra riktningspunkt |
| point3 | java.awt.geom.Point2D.Float | Slutpunkt |
| index | long | Index för segment i PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Lägger till en kubisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkten |
| y1 | float | Y-koordinat för första riktningspunkten |
| x2 | float | X-koordinat för andra riktningspunkten |
| y2 | float | Y-koordinat för andra riktningspunkten |
| x3 | float | X-koordinat för slutpunkten |
| y3 | float | Y-koordinat för slutpunkten |
| index | long | Index för segment i PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Lägger till en kvadratisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Slutpunkt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Lägger till en kvadratisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för riktningspunkt |
| y1 | float | Y-koordinat för riktningspunkt |
| x2 | float | X-koordinat för slutpunkt |
| y2 | float | Y-koordinat för slutpunkt |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Lägger till en kvadratisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Slutpunkt |
| index | long | Index för segment i PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Lägger till en kvadratisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för riktningspunkt |
| y1 | float | Y-koordinat för riktningspunkt |
| x2 | float | X-koordinat för slutpunkt |
| y2 | float | Y-koordinat för slutpunkt |
| index | long | Index för segment i PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Stänger den aktuella figuren i denna bana

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

Ställer in nästa punkts position.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Punktposition |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Ställer in nästa punkts position.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Lägger till den angivna bågen till banan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | float | Bredd på rektangeln |
| heigth | float | Höjd på rektangeln |
| startAngle | float | Startvinkel. |
| sweepAngle | float | Sweep angle/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Ställer in fyllningsläge

**Returnerar:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Ställer in fyllningsläge

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Ställer in penselns utseende

**Returnerar:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Ställer in penselns utseende

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |