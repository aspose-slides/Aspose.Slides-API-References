---
title: DrawClosedCurve()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kalemi kullanarak kapalı bir spline çizer.
type: docs
weight: 781
url: /tr/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) metod

Belirtilen kalemi kullanarak kapalı bir spline çizer.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Spline çizerken kullanılacak bir kalem |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) nokta, spline'i belirler |
| tension | **float** | Spline'in gerilimini belirten değer |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | YOK SAYILDI |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) metod

Belirtilen kalemi kullanarak kapalı bir spline çizer.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing::FillMode::Alternate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Spline çizerken kullanılacak bir kalem |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) nokta, spline'i belirler |
| tension | **float** | Spline'in gerilimini belirten değer |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | YOK SAYILDI |

## See Also

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)