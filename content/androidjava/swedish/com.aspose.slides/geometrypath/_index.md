---
title: GeometryPath
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar geometrisk sökväg för GeometryShape
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

Representerar geometri-sökväg för GeometryShape
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Skapar en instans av GeometryPath |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPathData()](#getPathData--) | Returnerar geometri-sökväg för GeometryShape som en array av sökvägssegment. |
| [removeAt(int index)](#removeAt-int-) | Tar bort segment vid angivet index i geometri-sökvägen. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Lägger till linje i slutet av sökvägen |
| [lineTo(float x, float y)](#lineTo-float-float-) | Lägger till linje i slutet av sökvägen |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Lägger till linje på den angivna platsen i sökvägen |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Lägger till linje på den angivna platsen i sökvägen |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Lägger till kubisk Bezier-kurva i slutet av sökvägen |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Lägger till kubisk Bezier-kurva i slutet av sökvägen |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Lägger till kubisk Bezier-kurva på den angivna platsen i sökvägen |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Lägger till kubisk Bezier-kurva på den angivna platsen i sökvägen |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Lägger till kvadratisk Bezier-kurva i slutet av sökvägen |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Lägger till kvadratisk Bezier-kurva i slutet av sökvägen |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Lägger till kvadratisk Bezier-kurva på den angivna platsen i sökvägen |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Lägger till kvadratisk Bezier-kurva på den angivna platsen i sökvägen |
| [closeFigure()](#closeFigure--) | Stänger den aktuella figuren i denna sökväg |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Ställer in nästa punktposition. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ställer in nästa punktposition. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Lägger till den angivna bågen till sökvägen. |
| [getFillMode()](#getFillMode--) | Ställer in fyllningsläge |
| [setFillMode(byte value)](#setFillMode-byte-) | Ställer in fyllningsläge |
| [getStroke()](#getStroke--) | Ställer in linjestil |
| [setStroke(boolean value)](#setStroke-boolean-) | Ställer in linjestil |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


Skapar en instans av GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```


Returnerar geometri-sökväg för GeometryShape som en array av sökvägssegment.

**Returnerar:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort segment vid angivet index i geometri-sökvägen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den geometri-sökväg som ska tas bort. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```


Lägger till linje i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | android.graphics.PointF | Slutpunkt för linjen |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```


Lägger till linje i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för linjens slutpunkt |
| y | float | Y-koordinat för linjens slutpunkt |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```


Lägger till linje på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | android.graphics.PointF | Slutpunkt |
| index | long | Index för segment i PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


Lägger till linje på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |
| index | long | Index för segment i PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


Lägger till kubisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Första riktningspunkt |
| point2 | android.graphics.PointF | Andra riktningspunkt |
| point3 | android.graphics.PointF | Slutpunkt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Lägger till kubisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkt |
| y1 | float | Y-koordinat för första riktningspunkt |
| x2 | float | X-koordinat för andra riktningspunkt |
| y2 | float | Y-koordinat för andra riktningspunkt |
| x3 | float | X-koordinat för slutpunkt |
| y3 | float | Y-koordinat för slutpunkt |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


Lägger till kubisk Bezier-kurva på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Första riktningspunkt |
| point2 | android.graphics.PointF | Andra riktningspunkt |
| point3 | android.graphics.PointF | Slutpunkt |
| index | long | Index för segment i PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Lägger till kubisk Bezier-kurva på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkt |
| y1 | float | Y-koordinat för första riktningspunkt |
| x2 | float | X-koordinat för andra riktningspunkt |
| y2 | float | Y-koordinat för andra riktningspunkt |
| x3 | float | X-koordinat för slutpunkt |
| y3 | float | Y-koordinat för slutpunkt |
| index | long | Index för segment i PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```


Lägger till kvadratisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Riktningspunkt |
| point2 | android.graphics.PointF | Slutpunkt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Lägger till kvadratisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för riktningspunkt |
| y1 | float | Y-koordinat för riktningspunkt |
| x2 | float | X-koordinat för slutpunkt |
| y2 | float | Y-koordinat för slutpunkt |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```


Lägger till kvadratisk Bezier-kurva på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Riktningspunkt |
| point2 | android.graphics.PointF | Slutpunkt |
| index | long | Index för segment i PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Lägger till kvadratisk Bezier-kurva på den angivna platsen i sökvägen

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


Stänger den aktuella figuren i denna sökväg

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```


Ställer in nästa punktposition.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | android.graphics.PointF | Punktposition |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


Ställer in nästa punktposition.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Lägger till den angivna bågen till sökvägen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | float | Bredd på rektangeln |
| heigth | float | Höjd på rektangeln |
| startAngle | float | Startvinkel. |
| sweepAngle | float | Svepningsvinkel/ |

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


Ställer in linjestil

**Returnerar:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


Ställer in linjestil

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |