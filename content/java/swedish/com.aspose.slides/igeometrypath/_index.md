---
title: IGeometryPath
second_title: Aspose.Slides for Java API Reference
description: Representerar geometri-sökväg för GeometryShape
type: docs
url: /sv/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Representerar geometri-sökväg för GeometryShape
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPathData()](#getPathData--) | Returnerar geometri-sökväg för GeometryShape som en array av sökvägssegment. |
| [removeAt(int index)](#removeAt-int-) | Tar bort segmentet på det angivna indexet i geometri-sökvägen. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Lägger till en linje i slutet av sökvägen |
| [lineTo(float x, float y)](#lineTo-float-float-) | Lägger till en linje i slutet av sökvägen |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Lägger till en linje på den angivna platsen i sökvägen |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Lägger till en linje på den angivna platsen i sökvägen |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Lägger till en kubisk Bezier-kurva i slutet av sökvägen |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Lägger till en kubisk Bezier-kurva i slutet av sökvägen |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Lägger till en kubisk Bezier-kurva på den angivna platsen i sökvägen |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Lägger till en kubisk Bezier-kurva på den angivna platsen i sökvägen |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Lägger till en kvadratisk Bezier-kurva i slutet av sökvägen |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Lägger till en kvadratisk Bezier-kurva i slutet av sökvägen |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Lägger till en kvadratisk Bezier-kurva på den angivna platsen i sökvägen |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Lägger till en kvadratisk Bezier-kurva på den angivna platsen i sökvägen |
| [closeFigure()](#closeFigure--) | Stänger den aktuella figuren i denna sökväg |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Ställer in nästa punktposition. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ställer in nästa punktposition. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Lägger till den angivna bågen till sökvägen. |
| [getFillMode()](#getFillMode--) | Ställer in fyllningsläge |
| [setFillMode(byte value)](#setFillMode-byte-) | Ställer in fyllningsläge |
| [getStroke()](#getStroke--) | Ställer in strekningsutseende |
| [setStroke(boolean value)](#setStroke-boolean-) | Ställer in strekningsutseende |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

Returnerar geometri-sökväg för GeometryShape som en array av sökvägssegment.

**Returnerar:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort segmentet på det angivna indexet i geometri-sökvägen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den geometri-sökväg som ska tas bort. |
### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public abstract void lineTo(Point2D.Float point)
```

Lägger till en linje i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Slutpunkt för linjen |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Lägger till en linje i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för linjens slutpunkt |
| y | float | Y-koordinat för linjens slutpunkt |
### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public abstract void lineTo(Point2D.Float point, long index)
```

Lägger till en linje på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Slutpunkt |
| index | long | Index för segmentet i PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Lägger till en linje på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |
| index | long | Index för segmentet i PathData |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Lägger till en kubisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Första riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Andra riktningspunkt |
| point3 | java.awt.geom.Point2D.Float | Slutpunkt |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Lägger till en kubisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkt |
| y1 | float | Y-koordinat för första riktningspunkt |
| x2 | float | X-koordinat för andra riktningspunkt |
| y2 | float | Y-koordinat för andra riktningspunkt |
| x3 | float | X-koordinat för slutpunkt |
| y3 | float | Y-koordinat för slutpunkt |
### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Lägger till en kubisk Bezier-kurva på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Första riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Andra riktningspunkt |
| point3 | java.awt.geom.Point2D.Float | Slutpunkt |
| index | long | Index för segmentet i PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Lägger till en kubisk Bezier-kurva på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för första riktningspunkt |
| y1 | float | Y-koordinat för första riktningspunkt |
| x2 | float | X-koordinat för andra riktningspunkt |
| y2 | float | Y-koordinat för andra riktningspunkt |
| x3 | float | X-koordinat för slutpunkt |
| y3 | float | Y-koordinat för slutpunkt |
| index | long | Index för segmentet i PathData |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Lägger till en kvadratisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Slutpunkt |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Lägger till en kvadratisk Bezier-kurva i slutet av sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för riktningspunkt |
| y1 | float | Y-koordinat för riktningspunkt |
| x2 | float | X-koordinat för slutpunkt |
| y2 | float | Y-koordinat för slutpunkt |
### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public abstract void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Lägger till en kvadratisk Bezier-kurva på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Riktningspunkt |
| point2 | java.awt.geom.Point2D.Float | Slutpunkt |
| index | long | Index för segmentet i PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Lägger till en kvadratisk Bezier-kurva på den angivna platsen i sökvägen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 | float | X-koordinat för riktningspunkt |
| y1 | float | Y-koordinat för riktningspunkt |
| x2 | float | X-koordinat för slutpunkt |
| y2 | float | Y-koordinat för slutpunkt |
| index | long | Index för segmentet i PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Stänger den aktuella figuren i denna sökväg
### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public abstract void moveTo(Point2D.Float point)
```

Ställer in nästa punktposition.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Punktposition |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Ställer in nästa punktposition.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinat för punkten |
| y | float | Y-koordinat för punkten |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Lägger till den angivna bågen till sökvägen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | float | Bredd på rektangeln |
| heigth | float | Höjd på rektangeln |
| startAngle | float | Startvinkel. |
| sweepAngle | float | Svepvinkel/ |
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

Ställer in strekningsutseende

**Returnerar:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Ställer in strekningsutseende

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |