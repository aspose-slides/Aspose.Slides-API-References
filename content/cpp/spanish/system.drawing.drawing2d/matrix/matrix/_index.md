---
title: Matrix()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de la clase Matrix que representa una matriz identidad.
type: docs
weight: 1
url: /es/system.drawing.drawing2d/matrix/matrix/
---
## Matrix::Matrix() constructor

Construye una nueva instancia de la clase [Matrix](../) que representa una matriz identidad.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix()
```

## Matrix::Matrix(float, float, float, float, float, float) constructor

Construye una nueva instancia de la clase [Matrix](../) e inicializa con los valores especificados.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(float m11, float m12, float m21, float m22, float dx, float dy)
```

### Arguments

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| m11 | **float** | El valor de la fila 1, columna 1 |
| m12 | **float** | El valor de la fila 1, columna 2 |
| m21 | **float** | El valor de la fila 2, columna 1 |
| m22 | **float** | El valor de la fila 2, columna 2 |
| dx | **float** | El valor de la fila 3, columna 1 |
| dy | **float** | El valor de la fila 3, columna 2 |

## Matrix::Matrix(const Rectangle\&, const ArrayPtr\<Point\>\&) constructor

Construye una nueva instancia de la clase [Matrix](../) para la transformación geométrica definida por el rectángulo y el arreglo de puntos especificados.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const Rectangle &rect, const ArrayPtr<Point> &plgpts)
```

## Matrix::Matrix(const RectangleF\&, const ArrayPtr\<PointF\>\&) constructor

Construye una nueva instancia de la clase [Matrix](../) para la transformación geométrica definida por el rectángulo y el arreglo de puntos especificados.

```cpp
System::Drawing::Drawing2D::Matrix::Matrix(const RectangleF &rect, const ArrayPtr<PointF> &plgpts)
```

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Matrix](../)
* Clase [Rectangle](../../../system.drawing/rectangle/)
* Clase [Point](../../../system.drawing/point/)
* Clase [RectangleF](../../../system.drawing/rectanglef/)
* Clase [PointF](../../../system.drawing/pointf/)
* Espacio de nombres [System::Drawing::Drawing2D](../../)
* Biblioteca [Aspose.Slides](../../../)