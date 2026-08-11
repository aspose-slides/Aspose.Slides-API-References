---
title: GraphicsPath()
second_title: مرجع API Aspose.Slides برای C++
description: یک نمونه جدید از کلاس GraphicsPath را با حالت پر کردن مشخص‌شده می‌سازد.
type: docs
weight: 1
url: /fa/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) سازنده

یک نمونه جدید از کلاس [GraphicsPath](../) را با حالت پر کردن مشخص شده می‌سازد.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | مشخص می‌کند که داخل مسیر بسته‌ای که توسط شیء ایجاد شده نمایان می‌شود چگونه پر شود |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) سازنده

یک نمونه جدید از شیء [GraphicsPath](../) که مسیر مشخص‌شده را نشان می‌دهد می‌سازد.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | آرایه‌ای شامل نقاطی که مسیر نمایان‌شده توسط شیء ایجاد شده را تعیین می‌کند |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای شامل مقادیری که نوع نقاط متناظر را در آرایه **pts** مشخص می‌کند |
| fillMode | [FillMode](../../fillmode/) | مشخص می‌کند که داخل مسیر بسته‌ای که توسط شیء ایجاد شده نمایان می‌شود چگونه پر شود |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) سازنده

یک نمونه جدید از شیء [GraphicsPath](../) که مسیر مشخص‌شده را نشان می‌دهد می‌سازد.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | آرایه‌ای شامل نقاطی که مسیر نمایان‌شده توسط شیء ایجاد شده را تعیین می‌کند |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | آرایه‌ای شامل مقادیری که نوع نقاط متناظر را در آرایه **pts** مشخص می‌کند |
| fillMode | [FillMode](../../fillmode/) | مشخص می‌کند که داخل مسیر بسته‌ای که توسط شیء ایجاد شده نمایان می‌شود چگونه پر شود |

## GraphicsPath::GraphicsPath(const SkPath\&) سازنده

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## مراجع

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [GraphicsPath](../)
* کلاس [Point](../../../system.drawing/point/)
* کلاس [PointF](../../../system.drawing/pointf/)
* فضای‌نام [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)