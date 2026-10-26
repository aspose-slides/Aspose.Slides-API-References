---
title: DrawClosedCurve()
second_title: مرجع API Aspose.Slides للغة C++
description: يرسم منحنىً مغلقًا باستخدام القلم المحدد.
type: docs
weight: 781
url: /ar/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) method

يرسم منحنىً مغلقًا باستخدام القلم المحدد.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم يُستخدم عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| tension | **float** | القيمة التي تحدد توتر المنحنى |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | متجاهل |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) method

يرسم منحنىً مغلقًا باستخدام القلم المحدد.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم يُستخدم عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| tension | **float** | القيمة التي تحدد توتر المنحنى |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | متجاهل |

## انظر أيضا

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [Pen](../../pen/)
* فئة [Point](../../point/)
* فئة [Graphics](../)
* فئة [PointF](../../pointf/)
* مساحة الاسم [System::Drawing](../../)
* Library [Aspose.Slides](../../../)