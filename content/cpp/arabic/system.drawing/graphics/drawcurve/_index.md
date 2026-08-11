---
title: DrawCurve()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يرسم منحنى من نوع spline باستخدام القلم المحدد.
type: docs
weight: 794
url: /ar/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) طريقة

يرسم منحنى من نوع spline باستخدام القلم المحدد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| tension | **float** | القيمة التي تحدد توتر المنحنى |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) طريقة

يرسم منحنى من نوع spline باستخدام القلم المحدد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| tension | **float** | القيمة التي تحدد توتر المنحنى |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) طريقة

يرسم منحنى من نوع spline باستخدام القلم المحدد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| offset | **int32_t** | الإزاحة من العنصر الأول في مصفوفة **points** |
| numberOfSegments | **int32_t** | عدد القطع لتضمينها في المنحنى |
| tension | **float** | القيمة التي تحدد توتر المنحنى |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) طريقة

يرسم منحنى من نوع spline باستخدام القلم المحدد.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | قلم لاستخدامه عند رسم المنحنى |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) من النقاط التي تحدد المنحنى |
| offset | **int32_t** | الإزاحة من العنصر الأول في مصفوفة **points** |
| numberOfSegments | **int32_t** | عدد القطع لتضمينها في المنحنى |
| tension | **float** | القيمة التي تحدد توتر المنحنى |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [Pen](../../pen/)
* فئة [Point](../../point/)
* فئة [Graphics](../)
* فئة [PointF](../../pointf/)
* مساحة الاسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)