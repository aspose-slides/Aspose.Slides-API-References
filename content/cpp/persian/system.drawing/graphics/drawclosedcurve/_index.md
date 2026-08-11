---
title: DrawClosedCurve()
second_title: مرجع API Aspose.Slides برای C++
description: یک منحنی بسته با استفاده از قلم مشخص‌شده می‌کشد.
type: docs
weight: 781
url: /fa/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) متد

یک منحنی بسته با استفاده از قلم مشخص‌شده می‌کشد.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلمی که برای رسم منحنی استفاده می‌شود |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) نقاطی که منحنی را تعیین می‌کند |
| tension | **float** | مقداری که کشش منحنی را مشخص می‌کند |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | نادیده |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) متد

یک منحنی بسته با استفاده از قلم مشخص‌شده می‌کشد.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلمی که برای رسم منحنی استفاده می‌شود |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) نقاطی که منحنی را تعیین می‌کند |
| tension | **float** | مقداری که کشش منحنی را مشخص می‌کند |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | نادیده |

## موارد مرتبط

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Pen](../../pen/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)