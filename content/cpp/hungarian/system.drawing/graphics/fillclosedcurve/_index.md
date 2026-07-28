---
title: FillClosedCurve()
second_title: Aspose.Slides for C++ API referencia
description: Lezárt spline-t rajzol a megadott ecset használatával.
type: docs
weight: 807
url: /hu/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) metódus

Lezárt spline-t rajzol a megadott brush használatával.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A brush, amelyet a spline rajzolásához használnak |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) pontok, amelyek meghatározzák a spline-t |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | FIGYELMEN KÍVÜL |
| tension | **float** | A spline feszültségét megadó érték |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) metódus

Lezárt spline-t rajzol a megadott brush használatával.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A brush, amelyet a spline rajzolásához használnak |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) pontok, amelyek meghatározzák a spline-t |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | FIGYELMEN KÍVÜL |
| tension | **float** | A spline feszültségét megadó érték |

## Lásd még

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [Graphics](../)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)