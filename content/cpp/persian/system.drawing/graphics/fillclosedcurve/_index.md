---
title: FillClosedCurve()
second_title: Aspose.Slides برای C++ مرجع API
description: یک اسپلاین بسته را با استفاده از Brush مشخص‌شده می‌کشد.
type: docs
weight: 807
url: /fa/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) متد

یک اسپلاین بسته را با استفاده از براش مشخص‌شده می‌کشد.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | یک براش برای استفاده هنگام رسم اسپلاین |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) از نقاط که اسپلاین را تعیین می‌کند |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | نادیده گرفته شده |
| tension | **float** | مقداری که کشش اسپلاین را مشخص می‌کند |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) متد

یک اسپلاین بسته را با استفاده از براش مشخص‌شده می‌کشد.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | یک براش برای استفاده هنگام رسم اسپلاین |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) از نقاط که اسپلاین را تعیین می‌کند |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | نادیده گرفته شده |
| tension | **float** | مقداری که کشش اسپلاین را مشخص می‌کند |

## موارد مرتبط

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [Brush](../../brush/)
* کلاس [PointF](../../pointf/)
* کلاس [Graphics](../)
* کلاس [Point](../../point/)
* فضای‌نام [System::Drawing](../../)
* Library [Aspose.Slides](../../../)