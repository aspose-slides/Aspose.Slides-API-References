---
title: DrawCurve()
second_title: مرجع API Aspose.Slides برای C++
description: یک اسپلین را با قلم مشخص شده می‌کشد.
type: docs
weight: 794
url: /fa/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) متد

یک اسپلین با قلم مشخص شده می‌کشد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک قلم برای استفاده هنگام رسم اسپلین |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) نقاطی که اسپلین را تعیین می‌کند |
| tension | **float** | مقداری که کشش اسپلین را مشخص می‌کند |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) متد

یک اسپلین با قلم مشخص شده می‌کشد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک قلم برای استفاده هنگام رسم اسپلین |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) نقاطی که اسپلین را تعیین می‌کند |
| tension | **float** | مقداری که کشش اسپلین را مشخص می‌کند |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) متد

یک اسپلین با قلم مشخص شده می‌کشد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک قلم برای استفاده هنگام رسم اسپلین |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) نقاطی که اسپلین را تعیین می‌کند |
| offset | **int32_t** | انحراف از عنصر اول در آرایه **points** |
| numberOfSegments | **int32_t** | تعداد بخش‌هایی که در منحنی گنجانده می‌شود |
| tension | **float** | مقداری که کشش اسپلین را مشخص می‌کند |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) متد

یک اسپلین با قلم مشخص شده می‌کشد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | یک قلم برای استفاده هنگام رسم اسپلین |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) نقاطی که اسپلین را تعیین می‌کند |
| offset | **int32_t** | انحراف از عنصر اول در آرایه **points** |
| numberOfSegments | **int32_t** | تعداد بخش‌هایی که در منحنی گنجانده می‌شود |
| tension | **float** | مقداری که کشش اسپلین را مشخص می‌کند |

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [Pen](../../pen/)
* کلاس [Point](../../point/)
* کلاس [Graphics](../)
* کلاس [PointF](../../pointf/)
* فضای‌نام [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)