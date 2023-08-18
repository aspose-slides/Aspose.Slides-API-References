---
title: Matrix()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance of Matrix class that represents an identity matrix.
type: docs
weight: 1
url: /system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() constructor


Constructs a new instance of [Matrix](../) class that represents an identity matrix.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) constructor


Constructs a new instance of [Matrix](../) class and initializes it with the specified values.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| m11 | **float** | The value of the 1-st row 1-st column |
| m12 | **float** | The value of the 1-st row 2-nd column |
| m21 | **float** | The value of the 2-nd row 1-st column |
| m22 | **float** | The value of the 2-nd row 2-nd column |
| dx | **float** | The value of the 3-rd row 1-st column |
| dy | **float** | The value of the 3-rd row 2-nd column |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) constructor


Constructs a new instance of the [Matrix](../) class to the geometric transform defined by the specified rectangle and array of points.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) constructor


Constructs a new instance of the [Matrix](../) class to the geometric transform defined by the specified rectangle and array of points.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Matrix](../)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Class [Point](../../../system.drawing/point/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)