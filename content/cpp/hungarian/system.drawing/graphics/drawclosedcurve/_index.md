---
title: DrawClosedCurve()
second_title: Aspose.Slides C++ API hivatkozás
description: Lezárt spline-t rajzol a megadott tollal.
type: docs
weight: 781
url: /hu/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) metódus

Lezárt spline-t rajzol a megadott tollal.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A toll, amelyet a spline rajzolásához használunk |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) pontok, amelyek meghatározzák a spline-t |
| tension | **float** | Az a érték, amely meghatározza a spline feszességét |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | FIGYELMEN KÍVÜL |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) metódus

Lezárt spline-t rajzol a megadott tollal.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | A toll, amelyet a spline rajzolásához használunk |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) pontok, amelyek meghatározzák a spline-t |
| tension | **float** | Az a érték, amely meghatározza a spline feszességét |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | FIGYELMEN KÍVÜL |

## Lásd még

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)