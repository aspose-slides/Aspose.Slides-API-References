---
title: GeometryPath
second_title: Aspose.Slides pro Android pomocí reference Java API
description: Reprezentuje geometrickou cestu objektu GeometryShape
type: docs
url: /cs/com.aspose.slides/geometrypath/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Reprezentuje geometrickou cestu objektu GeometryShape
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Vytvoří instanci GeometryPath |
## Metody

| Metoda | Popis |
| --- | --- |
| [getPathData()](#getPathData--) | Vrací geometrickou cestu objektu GeometryShape jako pole segmentů cesty. |
| [removeAt(int index)](#removeAt-int-) | Odstraní segment na zadaném indexu geometrické cesty. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Přidá čáru na konec cesty |
| [lineTo(float x, float y)](#lineTo-float-float-) | Přidá čáru na konec cesty |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Přidá čáru na zadané místo cesty |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Přidá čáru na zadané místo cesty |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Přidá kubickou Bézierovu křivku na konec cesty |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Přidá kubickou Bézierovu křivku na konec cesty |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Přidá kubickou Bézierovu křivku na zadané místo cesty |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Přidá kubickou Bézierovu křivku na zadané místo cesty |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Přidá kvadratickou Bézierovu křivku na zadané místo cesty |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Přidá kvadratickou Bézierovu křivku na zadané místo cesty |
| [closeFigure()](#closeFigure--) | Uzavře aktuální tvar této cesty |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Nastaví pozici dalšího bodu. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Nastaví pozici dalšího bodu. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Přidá zadaný oblouk do cesty. |
| [getFillMode()](#getFillMode--) | Nastaví režim výplně |
| [setFillMode(byte value)](#setFillMode-byte-) | Nastaví režim výplně |
| [getStroke()](#getStroke--) | Nastaví vzhled čáry |
| [setStroke(boolean value)](#setStroke-boolean-) | Nastaví vzhled čáry |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Vytvoří instanci GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Vrací geometrickou cestu objektu GeometryShape jako pole segmentů cesty.

**Vrací:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní segment na zadaném indexu geometrické cesty.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index geometrické cesty, který má být smazán. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```

Přidá čáru na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | android.graphics.PointF | Konec čáry |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Přidá čáru na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice koncového bodu čáry |
| y | float | Y-souřadnice koncového bodu čáry |

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```

Přidá čáru na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | android.graphics.PointF | Konec čáry |
| index | long | Index segmentu v PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Přidá čáru na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice bodu |
| y | float | Y-souřadnice bodu |
| index | long | Index segmentu v PathData |

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Přidá kubickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | První řídící bod |
| point2 | android.graphics.PointF | Druhý řídící bod |
| point3 | android.graphics.PointF | Konec čáry |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Přidá kubickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice prvního řídícího bodu |
| y1 | float | Y-souřadnice prvního řídícího bodu |
| x2 | float | X-souřadnice druhého řídícího bodu |
| y2 | float | Y-souřadnice druhého řídícího bodu |
| x3 | float | X-souřadnice koncového bodu |
| y3 | float | Y-souřadnice koncového bodu |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Přidá kubickou Bézierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | První řídící bod |
| point2 | android.graphics.PointF | Druhý řídící bod |
| point3 | android.graphics.PointF | Konec čáry |
| index | long | Index segmentu v PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Přidá kubickou Bézierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice prvního řídícího bodu |
| y1 | float | Y-souřadnice prvního řídícího bodu |
| x2 | float | X-souřadnice druhého řídícího bodu |
| y2 | float | Y-souřadnice druhého řídícího bodu |
| x3 | float | X-souřadnice koncového bodu |
| y3 | float | Y-souřadnice koncového bodu |
| index | long | Index segmentu v PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```

Přidá kvadratickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Řídící bod |
| point2 | android.graphics.PointF | Konec čáry |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Přidá kvadratickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice řídícího bodu |
| y1 | float | Y-souřadnice řídícího bodu |
| x2 | float | X-souřadnice koncového bodu |
| y2 | float | Y-souřadnice koncového bodu |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Přidá kvadratickou Bézierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Řídící bod |
| point2 | android.graphics.PointF | Konec čáry |
| index | long | Index segmentu v PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Přidá kvadratickou Bézierovu křivku na zadané místo cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice řídícího bodu |
| y1 | float | Y-souřadnice řídícího bodu |
| x2 | float | X-souřadnice koncového bodu |
| y2 | float | Y-souřadnice koncového bodu |
| index | long | Index segmentu v PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Uzavře aktuální tvar této cesty

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```

Nastaví pozici dalšího bodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | android.graphics.PointF | Pozice bodu |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Nastaví pozici dalšího bodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice bodu |
| y | float | Y-souřadnice bodu |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Přidá zadaný oblouk do cesty.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| width | float | Šířka obdélníku |
| heigth | float | Výška obdélníku |
| startAngle | float | Počáteční úhel. |
| sweepAngle | float | Úhlová šířka/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Nastaví režim výplně

**Vrací:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Nastaví režim výplně

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Nastaví vzhled čáry

**Vrací:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Nastaví vzhled čáry

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |