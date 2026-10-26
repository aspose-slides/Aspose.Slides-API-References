---
title: DrawCurve()
second_title: Aspose.Slides för C++ API-referens
description: Ritar en spline med den angivna pennan.
type: docs
weight: 794
url: /sv/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) metod

Ritar en spline med den angivna pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En pen att använda när spline ritas |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) av punkter som bestämmer spline |
| tension | **float** | Värde som anger spänningen för spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) metod

Ritar en spline med den angivna pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En pen att använda när spline ritas |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) av punkter som bestämmer spline |
| tension | **float** | Värde som anger spänningen för spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) metod

Ritar en spline med den angivna pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En pen att använda när spline ritas |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) av punkter som bestämmer spline |
| offset | **int32_t** | Offset från det första elementet i **points**-arrayen |
| numberOfSegments | **int32_t** | Antal segment att inkludera i kurvan |
| tension | **float** | Värde som anger spänningen för spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) metod

Ritar en spline med den angivna pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En pen att använda när spline ritas |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) av punkter som bestämmer spline |
| offset | **int32_t** | Offset från det första elementet i **points**-arrayen |
| numberOfSegments | **int32_t** | Antal segment att inkludera i kurvan |
| tension | **float** | Värde som anger spänningen för spline |

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Pen](../../pen/)
* Klass [Point](../../point/)
* Klass [Graphics](../)
* Klass [PointF](../../pointf/)
* Namnrymd [System::Drawing](../../)
* Library [Aspose.Slides](../../../)