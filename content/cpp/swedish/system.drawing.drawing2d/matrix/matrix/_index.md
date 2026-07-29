---
title: Matrix()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av klassen Matrix som representerar en identitetsmatris.
type: docs
weight: 1
url: /sv/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() konstruktor

Skapar en ny instans av klassen [Matrix](../) som representerar en identitetsmatris.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) konstruktor

Skapar en ny instans av klassen [Matrix](../) och initierar den med de angivna värdena.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| m11 | **float** | Värdet på den första raden första kolumnen |
| m12 | **float** | Värdet på den första raden andra kolumnen |
| m21 | **float** | Värdet på den andra raden första kolumnen |
| m22 | **float** | Värdet på den andra raden andra kolumnen |
| dx | **float** | Värdet på den tredje raden första kolumnen |
| dy | **float** | Värdet på den tredje raden andra kolumnen |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) konstruktor

Skapar en ny instans av klassen [Matrix](../) för den geometriska transformation som definieras av den angivna rektangeln och arrayen av punkter.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) konstruktor

Skapar en ny instans av klassen [Matrix](../) för den geometriska transformation som definieras av den angivna rektangeln och arrayen av punkter.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Matrix](../)
* Klass [Rectangle](../../../system.drawing/rectangle/)
* Klass [Point](../../../system.drawing/point/)
* Klass [RectangleF](../../../system.drawing/rectanglef/)
* Klass [PointF](../../../system.drawing/pointf/)
* Namnrymd [System::Drawing::Drawing2D](../../)
* Bibliotek [Aspose.Slides](../../../)