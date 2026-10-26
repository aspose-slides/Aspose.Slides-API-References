---
title: Matrix()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci třídy Matrix, která představuje jednotkovou matici.
type: docs
weight: 1
url: /cs/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() konstruktor


Vytvoří novou instanci třídy [Matrix](../) , která představuje jednotkovou matici.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) konstruktor


Vytvoří novou instanci třídy [Matrix](../) a inicializuje ji zadanými hodnotami.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| m11 | **float** | Hodnota 1. řádku 1. sloupce |
| m12 | **float** | Hodnota 1. řádku 2. sloupce |
| m21 | **float** | Hodnota 2. řádku 1. sloupce |
| m22 | **float** | Hodnota 2. řádku 2. sloupce |
| dx | **float** | Hodnota 3. řádku 1. sloupce |
| dy | **float** | Hodnota 3. řádku 2. sloupce |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) konstruktor


Vytvoří novou instanci třídy [Matrix](../) pro geometrickou transformaci definovanou zadaným obdélníkem a polem bodů.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) konstruktor


Vytvoří novou instanci třídy [Matrix](../) pro geometrickou transformaci definovanou zadaným obdélníkem a polem bodů.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix](../)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Point](../../../system.drawing/point/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)