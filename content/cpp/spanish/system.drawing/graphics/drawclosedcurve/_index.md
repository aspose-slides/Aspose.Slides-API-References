---
title: DrawClosedCurve()
second_title: Referencia de API de Aspose.Slides para C++
description: Dibuja una spline cerrada usando el lápiz especificado.
type: docs
weight: 781
url: /es/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) method


Dibuja una curva spline cerrada usando el lápiz especificado.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un lápiz para usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| tension | **float** | Valor que especifica la tensión de la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORADO |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) method


Dibuja una curva spline cerrada usando el lápiz especificado.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Un lápiz para usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| tension | **float** | Valor que especifica la tensión de la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORADO |

## Ver también

* Enumeración [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Definición de tipo [ArrayPtr](../../../system/arrayptr/)
* Clase [Pen](../../pen/)
* Clase [Point](../../point/)
* Clase [Graphics](../)
* Clase [PointF](../../pointf/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)