---
title: AddCurve()
second_title: Referencia de API de Aspose.Slides para C++
description: Agrega la curva especificada a la ruta representada por el objeto actual.
type: docs
weight: 274
url: /es/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) método


Agrega la curva especificada a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Puntos que especifican la curva |
| tension | **float** | Especifica la cantidad que la curva se dobla entre los puntos de control |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) método


Agrega la curva especificada a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Puntos que especifican la curva |
| tension | **float** | Especifica la cantidad que la curva se dobla entre los puntos de control |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) método


Agrega la curva especificada a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | Puntos que especifican la curva |
| offset | int | El índice del punto en **points** que se usa como el punto de inicio de la curva |
| number_of_segments | int | El número de segmentos usados para dibujar la curva |
| tension | **float** | Especifica la cantidad que la curva se dobla entre los puntos de control |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) método


Agrega la curva especificada a la ruta representada por el objeto actual.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | Puntos que especifican la curva |
| offset | int | El índice del punto en **points** que se usa como el punto de inicio de la curva |
| number_of_segments | int | El número de segmentos usados para dibujar la curva |
| tension | **float** | Especifica la cantidad que la curva se dobla entre los puntos de control |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)