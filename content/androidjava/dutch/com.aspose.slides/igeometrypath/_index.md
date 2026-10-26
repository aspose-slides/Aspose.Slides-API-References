---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /nl/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Stelt het geometriepad van GeometryShape voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPathData()](#getPathData--) | Retourneert het geometriepad van GeometryShape als een array van padsegmenten. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert segment op de opgegeven index van het geometriepad. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Voegt een lijn toe aan het einde van het pad |
| [lineTo(float x, float y)](#lineTo-float-float-) | Voegt een lijn toe aan het einde van het pad |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Voegt een lijn toe op de opgegeven plaats in het pad |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Voegt een lijn toe op de opgegeven plaats in het pad |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Voegt een kubieke Bezier-curve toe aan het einde van het pad |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Voegt een kubieke Bezier-curve toe op de opgegeven plaats in het pad |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Voegt een kubieke Bezier-curve toe op de opgegeven plaats in het pad |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Voegt een kwadratische Bezier-curve toe aan het einde van het pad |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats in het pad |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Voegt een kwadratische Bezier-curve toe op de opgegeven plaats in het pad |
| [closeFigure()](#closeFigure--) | Sluit de huidige figuur van dit pad |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Stelt de volgende puntpositie in. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Stelt de volgende puntpositie in. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Voegt de opgegeven boog toe aan het pad. |
| [getFillMode()](#getFillMode--) | Stelt vulmodus in |
| [setFillMode(byte value)](#setFillMode-byte-) | Stelt vulmodus in |
| [getStroke()](#getStroke--) | Stelt de weergave van de stroke in |
| [setStroke(boolean value)](#setStroke-boolean-) | Stelt de weergave van de stroke in |

### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

Retourneert het geometriepad van GeometryShape als een array van padsegmenten.

**Retour:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert segment op de opgegeven index van het geometriepad.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van het geometriepad dat moet worden verwijderd. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

Voegt een lijn toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | android.graphics.PointF | Eindpunt van de lijn |

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

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

Voegt een lijn toe op de opgegeven plaats in het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | android.graphics.PointF | Eindpunt |
| index | long | Index van segment in PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Voegt een lijn toe op de opgegeven plaats in het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | float | X-coördinaat van het punt |
| y | float | Y-coördinaat van het punt |
| index | long | Index van segment in PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
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
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
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
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Voegt een kubieke Bezier-curve toe op de opgegeven plaats in het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | android.graphics.PointF | Eerste richtpunt |
| point2 | android.graphics.PointF | Tweede richtpunt |
| point3 | android.graphics.PointF | Eindpunt |
| index | long | Index van segment in PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Voegt een kubieke Bezier-curve toe op de opgegeven plaats in het pad

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
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

Voegt een kwadratische Bezier-curve toe aan het einde van het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | android.graphics.PointF | Richtpunt |
| point2 | android.graphics.PointF | Eindpunt |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
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
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Voegt een kwadratische Bezier-curve toe op de opgegeven plaats in het pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point1 | android.graphics.PointF | Richtpunt |
| point2 | android.graphics.PointF | Eindpunt |
| index | long | Index van segment in PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Voegt een kwadratische Bezier-curve toe op de opgegeven plaats in het pad

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
public abstract void closeFigure()
```

Sluit de huidige figuur van dit pad

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

Stelt de volgende puntpositie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | android.graphics.PointF | Puntpositie |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Stelt de volgende puntpositie in.

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
| startAngle | float | Starthoek. |
| sweepAngle | float | Sweephoek/ |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Stelt vulmodus in

**Retour:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Stelt vulmodus in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

Stelt de weergave van de stroke in

**Retour:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Stelt de weergave van de stroke in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |