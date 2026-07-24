---
title: Matrix()
second_title: Aspose.Slides für C++ API-Referenz
description: Erzeugt eine neue Instanz der Klasse Matrix, die eine Einheitsmatrix darstellt.
type: docs
weight: 1
url: /de/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() Konstruktor

Erzeugt eine neue Instanz der Klasse [Matrix](../) , die eine Einheitsmatrix darstellt.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) Konstruktor

Erzeugt eine neue Instanz der Klasse [Matrix](../) und initialisiert sie mit den angegebenen Werten.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| m11 | **float** | Der Wert der 1. Zeile 1. Spalte |
| m12 | **float** | Der Wert der 1. Zeile 2. Spalte |
| m21 | **float** | Der Wert der 2. Zeile 1. Spalte |
| m22 | **float** | Der Wert der 2. Zeile 2. Spalte |
| dx | **float** | Der Wert der 3. Zeile 1. Spalte |
| dy | **float** | Der Wert der 3. Zeile 2. Spalte |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) Konstruktor

Erzeugt eine neue Instanz der Klasse [Matrix](../) für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt-Array definiert wird.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) Konstruktor

Erzeugt eine neue Instanz der Klasse [Matrix](../) für die geometrische Transformation, die durch das angegebene Rechteck und das Punkt-Array definiert wird.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Matrix](../)
* Klasse [Rectangle](../../../system.drawing/rectangle/)
* Klasse [Point](../../../system.drawing/point/)
* Klasse [RectangleF](../../../system.drawing/rectanglef/)
* Klasse [PointF](../../../system.drawing/pointf/)
* Namensraum [System::Drawing::Drawing2D](../../)
* Bibliothek [Aspose.Slides](../../../)