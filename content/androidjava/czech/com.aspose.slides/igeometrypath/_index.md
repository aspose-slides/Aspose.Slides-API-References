---
title: IGeometryPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represents geometry path of GeometryShape
type: docs
url: /cs/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Reprezentuje geometrickou cestu objektu GeometryShape
## Metody

| Metoda | Popis |
| --- | --- |
| [getPathData()](#getPathData--) | Vrací geometrickou cestu objektu GeometryShape jako pole úseků cesty. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje úsek na zadaném indexu geometrické cesty. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Přidá čáru na konec cesty |
| [lineTo(float x, float y)](#lineTo-float-float-) | Přidá čáru na konec cesty |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Přidá čáru na zadané místo cesty |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Přidá čáru na zadané místo cesty |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Přidá kubickou Bezierovu křivku na konec cesty |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Přidá kubickou Bezierovu křivku na konec cesty |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Přidá kubickou Bezierovu křivku na zadané místo cesty |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Přidá kubickou Bezierovu křivku na zadané místo cesty |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Přidá kvadratickou Bezierovu křivku na konec cesty |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Přidá kvadratickou Bezierovu křivku na konec cesty |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Přidá kvadratickou Bezierovu křivku na zadané místo cesty |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Přidá kvadratickou Bezierovu křivku na zadané místo cesty |
| [closeFigure()](#closeFigure--) | Uzavře aktuální figuru této cesty |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Nastaví pozici dalšího bodu. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Nastaví pozici dalšího bodu. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Přidá zadaný oblouk do cesty. |
| [getFillMode()](#getFillMode--) | Nastaví režim výplně |
| [setFillMode(byte value)](#setFillMode-byte-) | Nastaví režim výplně |
| [getStroke()](#getStroke--) | Nastaví vzhled tahu |
| [setStroke(boolean value)](#setStroke-boolean-) | Nastaví vzhled tahu |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

Vrací geometrickou cestu objektu GeometryShape jako pole úseků cesty.

**Vrací:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraňuje úsek na zadaném indexu geometrické cesty.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index geometrické cesty, který má být smazán. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

Přidá čáru na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | android.graphics.PointF | Konečný bod čáry |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Přidá čáru na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice koncového bodu čáry |
| y | float | Y-souřadnice koncového bodu čáry |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

Přidá čáru na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | android.graphics.PointF | Konečný bod |
| index | long | Index úseku v PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Přidá čáru na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice bodu |
| y | float | Y-souřadnice bodu |
| index | long | Index úseku v PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Přidá kubickou Bezierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | První řídicí bod |
| point2 | android.graphics.PointF | Druhý řídicí bod |
| point3 | android.graphics.PointF | Konečný bod |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Přidá kubickou Bezierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice prvního řídicího bodu |
| y1 | float | Y-souřadnice prvního řídicího bodu |
| x2 | float | X-souřadnice druhého řídicího bodu |
| y2 | float | Y-souřadnice druhého řídicího bodu |
| x3 | float | X-souřadnice konečného bodu |
| y3 | float | Y-souřadnice konečného bodu |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Přidá kubickou Bezierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | První řídicí bod |
| point2 | android.graphics.PointF | Druhý řídicí bod |
| point3 | android.graphics.PointF | Konečný bod |
| index | long | Index úseku v PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Přidá kubickou Bezierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice prvního řídicího bodu |
| y1 | float | Y-souřadnice prvního řídicího bodu |
| x2 | float | X-souřadnice druhého řídicího bodu |
| y2 | float | Y-souřadnice druhého řídicího bodu |
| x3 | float | X-souřadnice konečného bodu |
| y3 | float | Y-souřadnice konečného bodu |
| index | long | Index úseku v PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

Přidá kvadratickou Bezierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Řídicí bod |
| point2 | android.graphics.PointF | Konečný bod |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Přidá kvadratickou Bezierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice řídicího bodu |
| y1 | float | Y-souřadnice řídicího bodu |
| x2 | float | X-souřadnice konečného bodu |
| y2 | float | Y-souřadnice konečného bodu |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Přidá kvadratickou Bezierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Řídicí bod |
| point2 | android.graphics.PointF | Konečný bod |
| index | long | Index úseku v PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Přidá kvadratickou Bezierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice řídicího bodu |
| y1 | float | Y-souřadnice řídicího bodu |
| x2 | float | X-souřadnice konečného bodu |
| y2 | float | Y-souřadnice konečného bodu |
| index | long | Index úseku v PathData |

### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Uzavře aktuální figuru této cesty

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

Nastaví pozici dalšího bodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | android.graphics.PointF | Pozice bodu |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Nastaví pozici dalšího bodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice bodu |
| y | float | Y-souřadnice bodu |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Přidá zadaný oblouk do cesty.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | float | Šířka obdélníku |
| heigth | float | Výška obdélníku |
| startAngle | float | Počáteční úhel |
| sweepAngle | float | Úhel sweep |

### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Nastaví režim výplně

**Vrací:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Nastaví režim výplně

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

Nastaví vzhled tahu

**Vrací:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Nastaví vzhled tahu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |