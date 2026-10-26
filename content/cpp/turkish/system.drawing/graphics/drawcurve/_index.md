---
title: DrawCurve()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen kalemi kullanarak bir spline çizer.
type: docs
weight: 794
url: /tr/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) metot

Belirtilen kalemi kullanarak bir spline çizer.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Spline çizerken kullanılacak bir kalem |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) nokta spline'ı belirler |
| tension | **float** | Spline gerginliğini belirten değer |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) metot

Belirtilen kalemi kullanarak bir spline çizer.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Spline çizerken kullanılacak bir kalem |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) nokta spline'ı belirler |
| tension | **float** | Spline gerginliğini belirten değer |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) metot

Belirtilen kalemi kullanarak bir spline çizer.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Spline çizerken kullanılacak bir kalem |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) nokta spline'ı belirler |
| offset | **int32_t** | **points** dizisinin 1. elemanından ofset |
| numberOfSegments | **int32_t** | Eğriye dahil edilecek segment sayısı |
| tension | **float** | Spline gerginliğini belirten değer |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) metot

Belirtilen kalemi kullanarak bir spline çizer.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Spline çizerken kullanılacak bir kalem |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) nokta spline'ı belirler |
| offset | **int32_t** | **points** dizisinin 1. elemanından ofset |
| numberOfSegments | **int32_t** | Eğriye dahil edilecek segment sayısı |
| tension | **float** | Spline gerginliğini belirten değer |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Pen](../../pen/)
* Sınıf [Point](../../point/)
* Sınıf [Graphics](../)
* Sınıf [PointF](../../pointf/)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)