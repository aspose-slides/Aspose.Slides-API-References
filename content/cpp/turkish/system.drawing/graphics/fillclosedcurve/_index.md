---
title: FillClosedCurve()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen fırça kullanılarak kapalı bir spline çizer.
type: docs
weight: 807
url: /tr/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) method

Belirtilen fırça kullanılarak kapalı bir spline çizer.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Spline çizerken kullanılacak bir fırça |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) nokta kümesi, spline'ı belirler |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Spline gerilimini belirten değer |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) method

Belirtilen fırça kullanılarak kapalı bir spline çizer.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Spline çizerken kullanılacak bir fırça |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) nokta kümesi, spline'ı belirler |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | Spline gerilimini belirten değer |

## İlgili

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [PointF](../../pointf/)
* Class [Graphics](../)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)