---
title: GeometryPath
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje ścieżkę geometryczną obiektu GeometryShape
type: docs
url: /pl/com.aspose.slides/geometrypath/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGeometryPath](../../com.aspose.slides/igeometrypath)
```
public final class GeometryPath implements IGeometryPath
```

Reprezentuje ścieżkę geometryczną obiektu GeometryShape
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Tworzy instancję GeometryPath |
## Metody

| Metoda | Opis |
| --- | --- |
| [getPathData()](#getPathData--) | Zwraca ścieżkę geometryczną obiektu GeometryShape jako tablicę segmentów ścieżki. |
| [removeAt(int index)](#removeAt-int-) | Usuwa segment o określonym indeksie w ścieżce geometrycznej. |
| [lineTo(Point2D.Float point)](#lineTo-java.awt.geom.Point2D.Float-) | Dodaje linię na końcu ścieżki |
| [lineTo(float x, float y)](#lineTo-float-float-) | Dodaje linię na końcu ścieżki |
| [lineTo(Point2D.Float point, long index)](#lineTo-java.awt.geom.Point2D.Float-long-) | Dodaje linię w określonym miejscu ścieżki |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Dodaje linię w określonym miejscu ścieżki |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Dodaje krzywą Beziera trzeciego stopnia na końcu ścieżki |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Dodaje krzywą Beziera trzeciego stopnia na końcu ścieżki |
| [cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)](#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Dodaje krzywą Beziera trzeciego stopnia w określonym miejscu ścieżki |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Dodaje krzywą Beziera trzeciego stopnia w określonym miejscu ścieżki |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-) | Dodaje krzywą Beziera drugiego stopnia na końcu ścieżki |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Dodaje krzywą Beziera drugiego stopnia na końcu ścieżki |
| [quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)](#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-) | Dodaje krzywą Beziera drugiego stopnia w określonym miejscu ścieżki |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Dodaje krzywą Beziera drugiego stopnia w określonym miejscu ścieżki |
| [closeFigure()](#closeFigure--) | Zamyka bieżącą figurę tej ścieżki |
| [moveTo(Point2D.Float point)](#moveTo-java.awt.geom.Point2D.Float-) | Ustawia pozycję następnego punktu. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ustawia pozycję następnego punktu. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Dodaje określony łuk do ścieżki. |
| [getFillMode()](#getFillMode--) | Ustawia tryb wypełniania |
| [setFillMode(byte value)](#setFillMode-byte-) | Ustawia tryb wypełniania |
| [getStroke()](#getStroke--) | Ustawia wygląd obrysu |
| [setStroke(boolean value)](#setStroke-boolean-) | Ustawia wygląd obrysu |
### GeometryPath() {#GeometryPath--}
```
public GeometryPath()
```

Tworzy instancję GeometryPath

### getPathData() {#getPathData--}
```
public final IPathSegment[] getPathData()
```

Zwraca ścieżkę geometryczną obiektu GeometryShape jako tablicę segmentów ścieżki.

**Zwraca:**
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa segment o określonym indeksie w ścieżce geometrycznej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks ścieżki geometrycznej, który powinien zostać usunięty. |

### lineTo(Point2D.Float point) {#lineTo-java.awt.geom.Point2D.Float-}
```
public final void lineTo(Point2D.Float point)
```

Dodaje linię na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Punkt końcowy linii |

### lineTo(float x, float y) {#lineTo-float-float-}
```
public final void lineTo(float x, float y)
```

Dodaje linię na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X punktu końcowego linii |
| y | float | Współrzędna Y punktu końcowego linii |

### lineTo(Point2D.Float point, long index) {#lineTo-java.awt.geom.Point2D.Float-long-}
```
public final void lineTo(Point2D.Float point, long index)
```

Dodaje linię w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Punkt końcowy |
| index | long | Indeks segmentu w PathData |

### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public final void lineTo(float x, float y, long index)
```

Dodaje linię w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X punktu |
| y | float | Współrzędna Y punktu |
| index | long | Indeks segmentu w PathData |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3)
```

Dodaje krzywą Beziera trzeciego stopnia na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Pierwszy punkt kierunkowy |
| point2 | java.awt.geom.Point2D.Float | Drugi punkt kierunkowy |
| point3 | java.awt.geom.Point2D.Float | Punkt końcowy |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Dodaje krzywą Beziera trzeciego stopnia na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X pierwszego punktu kierunkowego |
| y1 | float | Współrzędna Y pierwszego punktu kierunkowego |
| x2 | float | Współrzędna X drugiego punktu kierunkowego |
| y2 | float | Współrzędna Y drugiego punktu kierunkowego |
| x3 | float | Współrzędna X punktu końcowego |
| y3 | float | Współrzędna Y punktu końcowego |

### cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index) {#cubicBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void cubicBezierTo(Point2D.Float point1, Point2D.Float point2, Point2D.Float point3, long index)
```

Dodaje krzywą Beziera trzeciego stopnia w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Pierwszy punkt kierunkowy |
| point2 | java.awt.geom.Point2D.Float | Drugi punkt kierunkowy |
| point3 | java.awt.geom.Point2D.Float | Punkt końcowy |
| index | long | Indeks segmentu w PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Dodaje krzywą Beziera trzeciego stopnia w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X pierwszego punktu kierunkowego |
| y1 | float | Współrzędna Y pierwszego punktu kierunkowego |
| x2 | float | Współrzędna X drugiego punktu kierunkowego |
| y2 | float | Współrzędna Y drugiego punktu kierunkowego |
| x3 | float | Współrzędna X punktu końcowego |
| y3 | float | Współrzędna Y punktu końcowego |
| index | long | Indeks segmentu w PathData |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2)
```

Dodaje krzywą Beziera drugiego stopnia na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Punkt kierunkowy |
| point2 | java.awt.geom.Point2D.Float | Punkt końcowy |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Dodaje krzywą Beziera drugiego stopnia na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X punktu kierunkowego |
| y1 | float | Współrzędna Y punktu kierunkowego |
| x2 | float | Współrzędna X punktu końcowego |
| y2 | float | Współrzędna Y punktu końcowego |

### quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index) {#quadraticBezierTo-java.awt.geom.Point2D.Float-java.awt.geom.Point2D.Float-long-}
```
public final void quadraticBezierTo(Point2D.Float point1, Point2D.Float point2, long index)
```

Dodaje krzywą Beziera drugiego stopnia w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | java.awt.geom.Point2D.Float | Punkt kierunkowy |
| point2 | java.awt.geom.Point2D.Float | Punkt końcowy |
| index | long | Indeks segmentu w PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Dodaje krzywą Beziera drugiego stopnia w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X punktu kierunkowego |
| y1 | float | Współrzędna Y punktu kierunkowego |
| x2 | float | Współrzędna X punktu końcowego |
| y2 | float | Współrzędna Y punktu końcowego |
| index | long | Indeks segmentu w PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```

Zamyka bieżącą figurę tej ścieżki

### moveTo(Point2D.Float point) {#moveTo-java.awt.geom.Point2D.Float-}
```
public final void moveTo(Point2D.Float point)
```

Ustawia pozycję następnego punktu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point | java.awt.geom.Point2D.Float | Pozycja punktu |

### moveTo(float x, float y) {#moveTo-float-float-}
```
public final void moveTo(float x, float y)
```

Ustawia pozycję następnego punktu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna X punktu |
| y | float | Współrzędna Y punktu |

### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public final void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Dodaje określony łuk do ścieżki.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| width | float | Szerokość prostokąta |
| heigth | float | Wysokość prostokąta |
| startAngle | float | Kąt początkowy. |
| sweepAngle | float | Kąt zakreślenia |

### getFillMode() {#getFillMode--}
```
public final byte getFillMode()
```

Ustawia tryb wypełniania

**Zwraca:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public final void setFillMode(byte value)
```

Ustawia tryb wypełniania

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getStroke() {#getStroke--}
```
public final boolean getStroke()
```

Ustawia wygląd obrysu

**Zwraca:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public final void setStroke(boolean value)
```

Ustawia wygląd obrysu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |