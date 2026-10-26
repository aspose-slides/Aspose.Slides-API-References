---
title: Matrix()
second_title: Aspose.Slides C++-re vonatkozó API hivatkozás
description: Létrehozza a Matrix osztály egy új példányát, amely egy egységmátrixot képvisel.
type: docs
weight: 1
url: /hu/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() konstruktor


Új példányt hoz létre a [Matrix](../) osztályból, amely egy egységmátrixot képvisel.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) konstruktor


Új példányt hoz létre a [Matrix](../) osztályból, és a megadott értékekkel inicializálja.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| m11 | **float** | Az 1. sor 1. oszlop értéke |
| m12 | **float** | Az 1. sor 2. oszlop értéke |
| m21 | **float** | Az 2. sor 1. oszlop értéke |
| m22 | **float** | Az 2. sor 2. oszlop értéke |
| dx | **float** | A 3. sor 1. oszlop értéke |
| dy | **float** | A 3. sor 2. oszlop értéke |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) konstruktor


Új példányt hoz létre a [Matrix](../) osztályból a megadott téglalap és ponttömb által meghatározott geometriai transzformációhoz.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) konstruktor


Új példányt hoz létre a [Matrix](../) osztályból a megadott téglalap és ponttömb által meghatározott geometriai transzformációhoz.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [Matrix](../)
* Osztály [Rectangle](../../../system.drawing/rectangle/)
* Osztály [Point](../../../system.drawing/point/)
* Osztály [RectangleF](../../../system.drawing/rectanglef/)
* Osztály [PointF](../../../system.drawing/pointf/)
* Névterület [System::Drawing::Drawing2D](../../)
* Könyvtár [Aspose.Slides](../../../)