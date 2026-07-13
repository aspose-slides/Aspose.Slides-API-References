---
title: GeometryPath
second_title: Aspose.Slides dla Androida – odniesienie API Java
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
## Konstruktorzy

| Konstruktor | Opis |
| --- | --- |
| [GeometryPath()](#GeometryPath--) | Tworzy instancję GeometryPath |
## Metody

| Metoda | Opis |
| --- | --- |
| [getPathData()](#getPathData--) | Zwraca ścieżkę geometryczną obiektu GeometryShape jako tablicę segmentów ścieżki. |
| [removeAt(int index)](#removeAt-int-) | Usuwa segment o podanym indeksie w ścieżce geometrycznej. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Dodaje linię na końcu ścieżki |
| [lineTo(float x, float y)](#lineTo-float-float-) | Dodaje linię na końcu ścieżki |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Dodaje linię w określonym miejscu ścieżki |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Dodaje linię w określonym miejscu ścieżki |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Dodaje krzywą Beziera stopnia trzeciego na końcu ścieżki |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Dodaje krzywą Beziera stopnia trzeciego na końcu ścieżki |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Dodaje krzywą Beziera stopnia drugiego na końcu ścieżki |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Dodaje krzywą Beziera stopnia drugiego na końcu ścieżki |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki |
| [closeFigure()](#closeFigure--) | Zamyka bieżącą figurę tej ścieżki |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Ustawia pozycję następnego punktu. |
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


Usuwa segment o podanym indeksie w ścieżce geometrycznej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks segmentu w ścieżce geometrycznej, który ma zostać usunięty. |

### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public final void lineTo(PointF point)
```


Dodaje linię na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point | android.graphics.PointF | Punkt końcowy linii |

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

### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public final void lineTo(PointF point, long index)
```


Dodaje linię w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point | android.graphics.PointF | Punkt końcowy |
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

### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```


Dodaje krzywą Beziera stopnia trzeciego na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Pierwszy punkt kontrolny |
| point2 | android.graphics.PointF | Drugi punkt kontrolny |
| point3 | android.graphics.PointF | Punkt końcowy |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```


Dodaje krzywą Beziera stopnia trzeciego na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X pierwszego punktu kontrolnego |
| y1 | float | Współrzędna Y pierwszego punktu kontrolnego |
| x2 | float | Współrzędna X drugiego punktu kontrolnego |
| y2 | float | Współrzędna Y drugiego punktu kontrolnego |
| x3 | float | Współrzędna X punktu końcowego |
| y3 | float | Współrzędna Y punktu końcowego |

### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```


Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Pierwszy punkt kontrolny |
| point2 | android.graphics.PointF | Drugi punkt kontrolny |
| point3 | android.graphics.PointF | Punkt końcowy |
| index | long | Indeks segmentu w PathData |

### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public final void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```


Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X pierwszego punktu kontrolnego |
| y1 | float | Współrzędna Y pierwszego punktu kontrolnego |
| x2 | float | Współrzędna X drugiego punktu kontrolnego |
| y2 | float | Współrzędna Y drugiego punktu kontrolnego |
| x3 | float | Współrzędna X punktu końcowego |
| y3 | float | Współrzędna Y punktu końcowego |
| index | long | Indeks segmentu w PathData |

### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public final void quadraticBezierTo(PointF point1, PointF point2)
```


Dodaje krzywą Beziera stopnia drugiego na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Punkt kontrolny |
| point2 | android.graphics.PointF | Punkt końcowy |

### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2)
```


Dodaje krzywą Beziera stopnia drugiego na końcu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X punktu kontrolnego |
| y1 | float | Współrzędna Y punktu kontrolnego |
| x2 | float | Współrzędna X punktu końcowego |
| y2 | float | Współrzędna Y punktu końcowego |

### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public final void quadraticBezierTo(PointF point1, PointF point2, long index)
```


Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point1 | android.graphics.PointF | Punkt kontrolny |
| point2 | android.graphics.PointF | Punkt końcowy |
| index | long | Indeks segmentu w PathData |

### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public final void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```


Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x1 | float | Współrzędna X punktu kontrolnego |
| y1 | float | Współrzędna Y punktu kontrolnego |
| x2 | float | Współrzędna X punktu końcowego |
| y2 | float | Współrzędna Y punktu końcowego |
| index | long | Indeks segmentu w PathData |

### closeFigure() {#closeFigure--}
```
public final void closeFigure()
```


Zamyka bieżącą figurę tej ścieżki

### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public final void moveTo(PointF point)
```


Ustawia pozycję następnego punktu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| point | android.graphics.PointF | Pozycja punktu |

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
| sweepAngle | float | Kąt zakreślenia/ |

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