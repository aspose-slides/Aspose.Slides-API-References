---
title: Matrix()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Tworzy nową instancję klasy Matrix, która reprezentuje macierz jednostkową.
type: docs
weight: 1
url: /pl/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() konstruktor

Tworzy nową instancję klasy [Matrix](../), która reprezentuje macierz jednostkową.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) konstruktor

Tworzy nową instancję klasy [Matrix](../) i inicjalizuje ją podanymi wartościami.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| m11 | **float** | Wartość pierwszego wiersza pierwszej kolumny |
| m12 | **float** | Wartość pierwszego wiersza drugiej kolumny |
| m21 | **float** | Wartość drugiego wiersza pierwszej kolumny |
| m22 | **float** | Wartość drugiego wiersza drugiej kolumny |
| dx | **float** | Wartość trzeciego wiersza pierwszej kolumny |
| dy | **float** | Wartość trzeciego wiersza drugiej kolumny |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) konstruktor

Tworzy nową instancję klasy [Matrix](../) dla transformacji geometrycznej określonej przez podany prostokąt i tablicę punktów.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) konstruktor

Tworzy nową instancję klasy [Matrix](../) dla transformacji geometrycznej określonej przez podany prostokąt i tablicę punktów.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [Matrix](../)
* Klasa [Rectangle](../../../system.drawing/rectangle/)
* Klasa [Point](../../../system.drawing/point/)
* Klasa [RectangleF](../../../system.drawing/rectanglef/)
* Klasa [PointF](../../../system.drawing/pointf/)
* Przestrzeń nazw [System::Drawing::Drawing2D](../../)
* Biblioteka [Aspose.Slides](../../../)