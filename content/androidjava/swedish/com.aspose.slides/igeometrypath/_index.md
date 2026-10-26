---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar geometrisk bana för GeometryShape
type: docs
url: /sv/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Representerar geometrisk bana för GeometryShape
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPathData()](#getPathData--) | Returnerar geometrisk bana för GeometryShape som en matris av segment. |
| [removeAt(int index)](#removeAt-int-) | Tar bort segmentet på det angivna indexet i geometrisk bana. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Lägger till linje i slutet av banan |
| [lineTo(float x, float y)](#lineTo-float-float-) | Lägger till linje i slutet av banan |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Lägger till linje på den angivna platsen i banan |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Lägger till linje på den angivna platsen i banan |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Lägger till kubisk Bezier-kurva i slutet av banan |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Lägger till kubisk Bezier-kurva i slutet av banan |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Lägger till kubisk Bezier-kurva på den angivna platsen i banan |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Lägger till kubisk Bezier-kurva på den angivna platsen i banan |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Lägger till kvadratisk Bezier-kurva i slutet av banan |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Lägger till kvadratisk Bezier-kurva i slutet av banan |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Lägger till kvadratisk Bezier-kurva på den angivna platsen i banan |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Lägger till kvadratisk Bezier-kurva på den angivna platsen i banan |
| [closeFigure()](#closeFigure--) | Stänger den aktuella figuren i denna bana |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Ställer in nästa punkts position. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ställer in nästa punkts position. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Lägger till den angivna bågen i banan. |
| [getFillMode()](#getFillMode--) | Ställer in fyllningsläge |
| [setFillMode(byte value)](#setFillMode-byte-) | Ställer in fyllningsläge |
| [getStroke()](#getStroke--) | Ställer in streckutseende |
| [setStroke(boolean value)](#setStroke-boolean-) | Ställer in streckutseende |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```


Returnerar geometrisk bana för GeometryShape som en matris av segment.

**Returnerar:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort segmentet på det angivna indexet i geometrisk bana.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den geometriska bana som ska tas bort. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```


Lägger till linje i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | android.graphics.PointF | Slutpunkt för linjen |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```


Lägger till linje i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för linjens slutpunkt |
| y | float | Y-koordinat för linjens slutpunkt |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```


Lägger till linje på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | android.graphics.PointF | Slutpunkt |
| index | long | Index för segmentet i PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```


Lägger till linje på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |
| index | long | Index för segmentet i PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


Lägger till kubisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Första riktningspunkten |
| point2 | android.graphics.PointF | Andra riktningspunkten |
| point3 | android.graphics.PointF | Slutpunkt |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Lägger till kubisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkten |
| y1 | float | Y-koordinat för första riktningspunkten |
| x2 | float | X-koordinat för andra riktningspunkten |
| y2 | float | Y-koordinat för andra riktningspunkten |
| x3 | float | X-koordinat för slutpunkten |
| y3 | float | Y-koordinat för slutpunkten |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


Lägger till kubisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Första riktningspunkten |
| point2 | android.graphics.PointF | Andra riktningspunkten |
| point3 | android.graphics.PointF | Slutpunkt |
| index | long | Index för segmentet i PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Lägger till kubisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkten |
| y1 | float | Y-koordinat för första riktningspunkten |
| x2 | float | X-koordinat för andra riktningspunkten |
| y2 | float | Y-koordinat för andra riktningspunkten |
| x3 | float | X-koordinat för slutpunkten |
| y3 | float | Y-koordinat för slutpunkten |
| index | long | Index för segmentet i PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```


Lägger till kvadratisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Riktningspunkt |
| point2 | android.graphics.PointF | Slutpunkt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Lägger till kvadratisk Bezier-kurva i slutet av banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för riktningspunkten |
| y1 | float | Y-koordinat för riktningspunkten |
| x2 | float | X-koordinat för slutpunkten |
| y2 | float | Y-koordinat för slutpunkten |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```


Lägger till kvadratisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | android.graphics.PointF | Riktningspunkt |
| point2 | android.graphics.PointF | Slutpunkt |
| index | long | Index för segmentet i PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Lägger till kvadratisk Bezier-kurva på den angivna platsen i banan

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för riktningspunkten |
| y1 | float | Y-koordinat för riktningspunkten |
| x2 | float | X-koordinat för slutpunkten |
| y2 | float | Y-koordinat för slutpunkten |
| index | long | Index för segmentet i PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```


Stänger den aktuella figuren i denna bana

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```


Ställer in nästa punkts position.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | android.graphics.PointF | Punktposition |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```


Ställer in nästa punkts position.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Lägger till den angivna bågen i banan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | float | Bredd på rektangeln |
| heigth | float | Höjd på rektangeln |
| startAngle | float | Startvinkel. |
| sweepAngle | float | Swep-vinkel/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```


Ställer in fyllningsläge

**Returnerar:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```


Ställer in fyllningsläge

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```


Ställer in streckutseende

**Returnerar:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```


Ställer in streckutseende

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |