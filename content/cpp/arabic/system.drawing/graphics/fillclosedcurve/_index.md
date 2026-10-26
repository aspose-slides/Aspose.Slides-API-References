---
title: FillClosedCurve()
second_title: مرجع API Aspose.Slides للغة C++
description: يرسم منحنىًا مغلقًا باستخدام الفرشاة المحددة.
type: docs
weight: 807
url: /ar/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) طريقة

يرسم منحنىً مغلقًا باستخدام الفرشاة المحددة.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | فرشاة تستخدم عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | متجاهل |
| tension | **float** | القيمة التي تحدد توتر المنحنى |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) طريقة

يرسم منحنىً مغلقًا باستخدام الفرشاة المحددة.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | فرشاة تستخدم عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | متجاهل |
| tension | **float** | القيمة التي تحدد توتر المنحنى |

## انظر أيضًا

* تعداد [FillMode](../../../system.drawing.drawing2d/fillmode/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Brush](../../brush/)
* فئة [PointF](../../pointf/)
* فئة [Graphics](../)
* فئة [Point](../../point/)
* مساحة أسماء [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)