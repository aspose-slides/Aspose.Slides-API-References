---
title: Matrix()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый экземпляр класса Matrix, представляющий единичную матрицу.
type: docs
weight: 1
url: /ru/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() конструктор

Создает новый экземпляр класса [Matrix](../), представляющего единичную матрицу.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) конструктор

Создает новый экземпляр класса [Matrix](../) и инициализирует его указанными значениями.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| m11 | **float** | Значение первой строки первого столбца |
| m12 | **float** | Значение первой строки второго столбца |
| m21 | **float** | Значение второй строки первого столбца |
| m22 | **float** | Значение второй строки второго столбца |
| dx | **float** | Значение третьей строки первого столбца |
| dy | **float** | Значение третьей строки второго столбца |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) конструктор

Создает новый экземпляр класса [Matrix](../) для геометрического преобразования, определенного указанным прямоугольником и массивом точек.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) конструктор

Создает новый экземпляр класса [Matrix](../) для геометрического преобразования, определенного указанным прямоугольником и массивом точек.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [Matrix](../)
* Класс [Rectangle](../../../system.drawing/rectangle/)
* Класс [Point](../../../system.drawing/point/)
* Класс [RectangleF](../../../system.drawing/rectanglef/)
* Класс [PointF](../../../system.drawing/pointf/)
* Пространство имен [System::Drawing::Drawing2D](../../)
* Библиотека [Aspose.Slides](../../../)