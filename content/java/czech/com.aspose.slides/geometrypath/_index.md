---
title: GeometryPath
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje geometrickou cestu objektu GeometryShape
type: docs
url: /cs/com.aspose.slides/geometrypath/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Reprezentuje geometrickou cestu objektu GeometryShape
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Vytvoří instanci třídy GeometryPath |
## Metody

| Metoda | Popis |
| --- | --- |
| [getPathData()](#getPathData--) | Vrací geometrickou cestu objektu GeometryShape jako pole segmentů cesty. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje segment na určeném indexu geometrické cesty. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Přidá čáru na konec cesty |
| [lineTo(float x, float y)](#lineTo-float-float-) | Přidá čáru na konec cesty |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Přidá čáru na určené místo v cestě |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Přidá čáru na určené místo v cestě |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Přidá kubickou Bézierovu křivku na konec cesty |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Přidá kubickou Bézierovu křivku na konec cesty |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Přidá kubickou Bézierovu křivku na určené místo v cestě |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Přidá kubickou Bézierovu křivku na určené místo v cestě |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Přidá kvadratickou Bézierovu křivku na konec cesty |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Přidá kvadratickou Bézierovu křivku na určené místo v cestě |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Přidá kvadratickou Bézierovu křivku na určené místo v cestě |
| [closeFigure()](#closeFigure--) | Uzavře aktuální figuru této cesty |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Nastaví pozici následujícího bodu. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Nastaví pozici následujícího bodu. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Přidá zadaný oblouk do cesty. |
| [getFillMode()](#getFillMode--) | Nastaví režim výplně |
| [setFillMode(byte value)](#setFillMode-byte-) | Nastaví režim výplně |
| [getStroke()](#getStroke--) | Nastaví vzhled tahu |
| [setStroke(boolean value)](#setStroke-boolean-) | Nastaví vzhled tahu |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


Vytvoří instanci třídy GeometryPath

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


Odstraňuje segment na určeném indexu geometrické cesty.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index geometrické cesty, který má být odstraněn. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```


Přidá čáru na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Konečný bod čáry |

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

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```


Přidá čáru na určené místo v cestě

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Konečný bod |
| index | long | Index segmentu v PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


Přidá čáru na určené místo v cestě

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x | float | X-souřadnice bodu |
| y | float | Y-souřadnice bodu |
| index | long | Index segmentu v PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Přidá kubickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | První řídicí bod |
| point2 | java.awt.geom.Point2D.Float | Druhý řídicí bod |
| point3 | java.awt.geom.Point2D.Float | Konečný bod |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Přidá kubickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice prvního řídicího bodu |
| y1 | float | Y-souřadnice prvního řídicího bodu |
| x2 | float | X-souřadnice druhého řídicího bodu |
| y2 | float | Y-souřadnice druhého řídicího bodu |
| x3 | float | X-souřadnice koncového bodu |
| y3 | float | Y-souřadnice koncového bodu |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Přidá kubickou Bézierovu křivku na určené místo v cestě

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | První řídicí bod |
| point2 | java.awt.geom.Point2D.Float | Druhý řídicí bod |
| point3 | java.awt.geom.Point2D.Float | Konečný bod |
| index | long | Index segmentu v PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Přidá kubickou Bézierovu křivku na určené místo v cestě

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice prvního řídicího bodu |
| y1 | float | Y-souřadnice prvního řídicího bodu |
| x2 | float | X-souřadnice druhého řídicího bodu |
| y2 | float | Y-souřadnice druhého řídicího bodu |
| x3 | float | X-souřadnice koncového bodu |
| y3 | float | Y-souřadnice koncového bodu |
| index | long | Index segmentu v PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Přidá kvadratickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Řídicí bod |
| point2 | java.awt.geom.Point2D.Float | Konečný bod |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Přidá kvadratickou Bézierovu křivku na konec cesty

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice řídicího bodu |
| y1 | float | Y-souřadnice řídicího bodu |
| x2 | float | X-souřadnice koncového bodu |
| y2 | float | Y-souřadnice koncového bodu |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Přidá kvadratickou Bézierovu křivku na určené místo v cestě

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Řídicí bod |
| point2 | java.awt.geom.Point2D.Float | Konečný bod |
| index | long | Index segmentu v PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Přidá kvadratickou Bézierovu křivku na určené místo v cestě

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| x1 | float | X-souřadnice řídicího bodu |
| y1 | float | Y-souřadnice řídicího bodu |
| x2 | float | X-souřadnice koncového bodu |
| y2 | float | Y-souřadnice koncového bodu |
| index | long | Index segmentu v PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


Uzavře aktuální figuru této cesty

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```


Nastaví pozici následujícího bodu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Pozice bodu |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


Nastaví pozici následujícího bodu.

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
| sweepAngle | float | Úhlový rozsah |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```


Získá režim výplně

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


Získá vzhled tahu

**Vrací:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


Nastaví vzhled tahu

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |