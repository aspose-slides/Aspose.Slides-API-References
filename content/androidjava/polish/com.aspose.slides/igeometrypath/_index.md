---
title: IGeometryPath
second_title: Aspose.Slides dla Androida przy użyciu Java API Reference
description: Reprezentuje ścieżkę geometryczną obiektu GeometryShape
type: docs
url: /pl/com.aspose.slides/igeometrypath/
---```
public interface IGeometryPath
```

Reprezentuje ścieżkę geometryczną obiektu GeometryShape
## Metody

| Metoda | Opis |
| --- | --- |
| [getPathData()](#getPathData--) | Zwraca ścieżkę geometryczną obiektu GeometryShape jako tablicę segmentów ścieżki. |
| [removeAt(int index)](#removeAt-int-) | Usuwa segment o podanym indeksie ścieżki geometrycznej. |
| [lineTo(PointF point)](#lineTo-android.graphics.PointF-) | Dodaje linię na koniec ścieżki |
| [lineTo(float x, float y)](#lineTo-float-float-) | Dodaje linię na koniec ścieżki |
| [lineTo(PointF point, long index)](#lineTo-android.graphics.PointF-long-) | Dodaje linię w określonym miejscu ścieżki |
| [lineTo(float x, float y, long index)](#lineTo-float-float-long-) | Dodaje linię w określonym miejscu ścieżki |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-) | Dodaje krzywą Beziera stopnia trzeciego na koniec ścieżki |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)](#cubicBezierTo-float-float-float-float-float-float-) | Dodaje krzywą Beziera stopnia trzeciego na koniec ścieżki |
| [cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)](#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-) | Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki |
| [cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)](#cubicBezierTo-float-float-float-float-float-float-long-) | Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki |
| [quadraticBezierTo(PointF point1, PointF point2)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-) | Dodaje krzywą Beziera stopnia drugiego na koniec ścieżki |
| [quadraticBezierTo(float x1, float y1, float x2, float y2)](#quadraticBezierTo-float-float-float-float-) | Dodaje krzywą Beziera stopnia drugiego na koniec ścieżki |
| [quadraticBezierTo(PointF point1, PointF point2, long index)](#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-) | Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki |
| [quadraticBezierTo(float x1, float y1, float x2, float y2, long index)](#quadraticBezierTo-float-float-float-float-long-) | Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki |
| [closeFigure()](#closeFigure--) | Zamyka bieżącą figurę tej ścieżki |
| [moveTo(PointF point)](#moveTo-android.graphics.PointF-) | Ustawia pozycję następnego punktu. |
| [moveTo(float x, float y)](#moveTo-float-float-) | Ustawia pozycję następnego punktu. |
| [arcTo(float width, float heigth, float startAngle, float sweepAngle)](#arcTo-float-float-float-float-) | Dodaje określony łuk do ścieżki. |
| [getFillMode()](#getFillMode--) | Ustawia tryb wypełnienia |
| [setFillMode(byte value)](#setFillMode-byte-) | Ustawia tryb wypełnienia |
| [getStroke()](#getStroke--) | Ustawia wygląd obrysu |
| [setStroke(boolean value)](#setStroke-boolean-) | Ustawia wygląd obrysu |
### getPathData() {#getPathData--}
```
public abstract IPathSegment[] getPathData()
```

**Zwraca:**  
com.aspose.slides.IPathSegment[]
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa segment o podanym indeksie ścieżki geometrycznej.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks ścieżki geometrycznej, który ma zostać usunięty. |
### lineTo(PointF point) {#lineTo-android.graphics.PointF-}
```
public abstract void lineTo(PointF point)
```

Dodaje linię na koniec ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | Punkt końcowy linii |
### lineTo(float x, float y) {#lineTo-float-float-}
```
public abstract void lineTo(float x, float y)
```

Dodaje linię na koniec ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Współrzędna X punktu końcowego linii |
| y | float | Współrzędna Y punktu końcowego linii |
### lineTo(PointF point, long index) {#lineTo-android.graphics.PointF-long-}
```
public abstract void lineTo(PointF point, long index)
```

Dodaje linię w określonym miejscu ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | Punkt końcowy |
| index | long | Indeks segmentu w PathData |
### lineTo(float x, float y, long index) {#lineTo-float-float-long-}
```
public abstract void lineTo(float x, float y, long index)
```

Dodaje linię w określonym miejscu ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Współrzędna X punktu |
| y | float | Współrzędna Y punktu |
| index | long | Indeks segmentu w PathData |
### cubicBezierTo(PointF point1, PointF point2, PointF point3) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3)
```

Dodaje krzywą Beziera stopnia trzeciego na koniec ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Pierwszy punkt kierunkowy |
| point2 | android.graphics.PointF | Drugi punkt kierunkowy |
| point3 | android.graphics.PointF | Punkt końcowy |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) {#cubicBezierTo-float-float-float-float-float-float-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3)
```

Dodaje krzywą Beziera stopnia trzeciego na koniec ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Współrzędna X pierwszego punktu kierunkowego |
| y1 | float | Współrzędna Y pierwszego punktu kierunkowego |
| x2 | float | Współrzędna X drugiego punktu kierunkowego |
| y2 | float | Współrzędna Y drugiego punktu kierunkowego |
| x3 | float | Współrzędna X punktu końcowego |
| y3 | float | Współrzędna Y punktu końcowego |
### cubicBezierTo(PointF point1, PointF point2, PointF point3, long index) {#cubicBezierTo-android.graphics.PointF-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void cubicBezierTo(PointF point1, PointF point2, PointF point3, long index)
```

Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Pierwszy punkt kierunkowy |
| point2 | android.graphics.PointF | Drugi punkt kierunkowy |
| point3 | android.graphics.PointF | Punkt końcowy |
| index | long | Indeks segmentu w PathData |
### cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index) {#cubicBezierTo-float-float-float-float-float-float-long-}
```
public abstract void cubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, long index)
```

Dodaje krzywą Beziera stopnia trzeciego w określonym miejscu ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Współrzędna X pierwszego punktu kierunkowego |
| y1 | float | Współrzędna Y pierwszego punktu kierunkowego |
| x2 | float | Współrzędna X drugiego punktu kierunkowego |
| y2 | float | Współrzędna Y drugiego punktu kierunkowego |
| x3 | float | Współrzędna X punktu końcowego |
| y3 | float | Współrzędna Y punktu końcowego |
| index | long | Indeks segmentu w PathData |
### quadraticBezierTo(PointF point1, PointF point2) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2)
```

Dodaje krzywą Beziera stopnia drugiego na koniec ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Punkt kierunkowy |
| point2 | android.graphics.PointF | Punkt końcowy |
### quadraticBezierTo(float x1, float y1, float x2, float y2) {#quadraticBezierTo-float-float-float-float-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2)
```

Dodaje krzywą Beziera stopnia drugiego na koniec ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Współrzędna X punktu kierunkowego |
| y1 | float | Współrzędna Y punktu kierunkowego |
| x2 | float | Współrzędna X punktu końcowego |
| y2 | float | Współrzędna Y punktu końcowego |
### quadraticBezierTo(PointF point1, PointF point2, long index) {#quadraticBezierTo-android.graphics.PointF-android.graphics.PointF-long-}
```
public abstract void quadraticBezierTo(PointF point1, PointF point2, long index)
```

Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| point1 | android.graphics.PointF | Punkt kierunkowy |
| point2 | android.graphics.PointF | Punkt końcowy |
| index | long | Indeks segmentu w PathData |
### quadraticBezierTo(float x1, float y1, float x2, float y2, long index) {#quadraticBezierTo-float-float-float-float-long-}
```
public abstract void quadraticBezierTo(float x1, float y1, float x2, float y2, long index)
```

Dodaje krzywą Beziera stopnia drugiego w określonym miejscu ścieżki

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | float | Współrzędna X punktu kierunkowego |
| y1 | float | Współrzędna Y punktu kierunkowego |
| x2 | float | Współrzędna X punktu końcowego |
| y2 | float | Współrzędna Y punktu końcowego |
| index | long | Indeks segmentu w PathData |
### closeFigure() {#closeFigure--}
```
public abstract void closeFigure()
```

Zamyka bieżącą figurę tej ścieżki
### moveTo(PointF point) {#moveTo-android.graphics.PointF-}
```
public abstract void moveTo(PointF point)
```

Ustawia pozycję następnego punktu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | android.graphics.PointF | Pozycja punktu |
### moveTo(float x, float y) {#moveTo-float-float-}
```
public abstract void moveTo(float x, float y)
```

Ustawia pozycję następnego punktu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Współrzędna X punktu |
| y | float | Współrzędna Y punktu |
### arcTo(float width, float heigth, float startAngle, float sweepAngle) {#arcTo-float-float-float-float-}
```
public abstract void arcTo(float width, float heigth, float startAngle, float sweepAngle)
```

Dodaje określony łuk do ścieżki.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Szerokość prostokąta |
| heigth | float | Wysokość prostokąta |
| startAngle | float | Kąt początkowy. |
| sweepAngle | float | Kąt przebiegu |
### getFillMode() {#getFillMode--}
```
public abstract byte getFillMode()
```

Ustawia tryb wypełnienia

**Zwraca:**
byte
### setFillMode(byte value) {#setFillMode-byte-}
```
public abstract void setFillMode(byte value)
```

Ustawia tryb wypełnienia

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getStroke() {#getStroke--}
```
public abstract boolean getStroke()
```

Ustawia wygląd obrysu

**Zwraca:**
boolean
### setStroke(boolean value) {#setStroke-boolean-}
```
public abstract void setStroke(boolean value)
```

Ustawia wygląd obrysu

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |