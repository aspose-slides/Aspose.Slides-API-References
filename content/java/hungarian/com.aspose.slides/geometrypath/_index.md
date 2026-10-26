---
title: GeometryPath
second_title: Aspose.Slides Java API Referenciája
description: A GeometryShape geometriai útvonalát reprezentálja
type: docs
url: /hu/com.aspose.slides/geometrypath/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

A GeometryShape geometriai útvonalát reprezentálja
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Létrehozza a GeometryPath példányt |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPathData()](#getPathData--) | Visszaadja a GeometryShape geometriai útvonalát útvonal szegmensek tömbjeként. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a szegmenst a geometriai útvonal megadott indexén. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Vonalat ad az útvonal végéhez |
| [lineTo(float x, float y)](#lineTo-float-float-) | Vonalat ad az útvonal végéhez |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Vonalat ad az útvonal megadott helyéhez |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Vonalat ad az útvonal megadott helyéhez |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Kúbikus Bézier-görbét ad az útvonal végéhez |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Kúbikus Bézier-görbét ad az útvonal végéhez |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Kúbikus Bézier-görbét ad az útvonal megadott helyéhez |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Kúbikus Bézier-görbét ad az útvonal megadott helyéhez |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Kvadratikus Bézier-görbét ad az útvonal végéhez |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Kvadratikus Bézier-görbét ad az útvonal végéhez |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Kvadratikus Bézier-görbét ad az útvonal megadott helyéhez |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Kvadratikus Bézier-görbét ad az útvonal megadott helyéhez |
| [closeFigure()](#closeFigure--) | Lezárja az útvonal jelenlegi alakját |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Beállítja a következő pont helyzetét. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Beállítja a következő pont helyzetét. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Hozzáadja a megadott ívet az útvonalhoz. |
| [getFillMode()](#getFillMode--) | Beállítja a kitöltési módot |
| [setFillMode(byte value)](#setFillMode-byte-) | Beállítja a kitöltési módot |
| [getStroke()](#getStroke--) | Beállítja a körvonal megjelenését |
| [setStroke(boolean value)](#setStroke-boolean-) | Beállítja a körvonal megjelenését |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```


Létrehozza a GeometryPath példányt

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```


Visszaadja a GeometryShape geometriai útvonalát útvonal szegmensek tömbjeként.

**Visszatér:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolítja a szegmenst a geometriai útvonal megadott indexén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő geometriai útvonal indexe. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```


Vonalat ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | A vonal végpontja |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```


Vonalat ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A vonal végpontjának X koordinátája |
| y | float | A vonal végpontjának Y koordinátája |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```


Vonalat ad az útvonal megadott helyéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Végpont |
| index | long | A szegmens indexe a PathData-ban |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```


Vonalat ad az útvonal megadott helyéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A pont X koordinátája |
| y | float | A pont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```


Kúbikus Bézier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Első iránypont |
| point2 | java.awt.geom.Point2D.Float | Második iránypont |
| point3 | java.awt.geom.Point2D.Float | Végpont |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Kúbikus Bézier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az első iránypont X koordinátája |
| y1 | float | Az első iránypont Y koordinátája |
| x2 | float | A második iránypont X koordinátája |
| y2 | float | A második iránypont Y koordinátája |
| x3 | float | A végpont X koordinátája |
| y3 | float | A végpont Y koordinátája |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```


Kúbikus Bézier-görbét ad az útvonal megadott helyéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Első iránypont |
| point2 | java.awt.geom.Point2D.Float | Második iránypont |
| point3 | java.awt.geom.Point2D.Float | Végpont |
| index | long | A szegmens indexe a PathData-ban |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Kúbikus Bézier-görbét ad az útvonal megadott helyéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Az első iránypont X koordinátája |
| y1 | float | Az első iránypont Y koordinátája |
| x2 | float | A második iránypont X koordinátája |
| y2 | float | A második iránypont Y koordinátája |
| x3 | float | A végpont X koordinátája |
| y3 | float | A végpont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```


Kvadratikus Bézier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Iránypont |
| point2 | java.awt.geom.Point2D.Float | Végpont |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Kvadratikus Bézier-görbét ad az útvonal végéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Iránypont X koordinátája |
| y1 | float | Iránypont Y koordinátája |
| x2 | float | Végpont X koordinátája |
| y2 | float | Végpont Y koordinátája |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```


Kvadratikus Bézier-görbét ad az útvonal megadott helyéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Iránypont |
| point2 | java.awt.geom.Point2D.Float | Végpont |
| index | long | A szegmens indexe a PathData-ban |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Kvadratikus Bézier-görbét ad az útvonal megadott helyéhez

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x1 | float | Iránypont X koordinátája |
| y1 | float | Iránypont Y koordinátája |
| x2 | float | Végpont X koordinátája |
| y2 | float | Végpont Y koordinátája |
| index | long | A szegmens indexe a PathData-ban |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


Lezárja az útvonal jelenlegi alakját

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```


Beállítja a következő pont helyzetét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Pont pozíciója |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```


Beállítja a következő pont helyzetét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | float | A pont X koordinátája |
| y | float | A pont Y koordinátája |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```


Hozzáadja a megadott ívet az útvonalhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| width | float | A téglalap szélessége |
| heigth | float | A téglalap magassága |
| startAngle | float | Kezdő szög. |
| sweepAngle | float | Átmeneti szög/ |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```


Beállítja a kitöltési módot

**Visszatér:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```


Beállítja a kitöltési módot

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```


Beállítja a körvonal megjelenését

**Visszatér:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```


Beállítja a körvonal megjelenését

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |