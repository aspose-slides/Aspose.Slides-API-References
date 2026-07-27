---
title: FillClosedCurve()
second_title: Referencia de la API de Aspose.Slides para C++
description: Dibuja una spline cerrada utilizando el brush especificado.
type: docs
weight: 807
url: /es/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) método

Dibuja una spline cerrada utilizando el brush especificado.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un brush para usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Valor que especifica la tension de la spline |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) método

Dibuja una spline cerrada utilizando el brush especificado.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un brush para usar al dibujar la spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) de puntos que determina la spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Valor que especifica la tension de la spline |

## Ver también

* Enumeración [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [Brush](../../brush/)
* Clase [PointF](../../pointf/)
* Clase [Graphics](../)
* Clase [Point](../../point/)
* Espacio de nombres [System::Drawing](../../)
* Biblioteca [Aspose.Slides](../../../)