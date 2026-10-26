---
title: DrawCurve()
second_title: Aspose.Slides pro C++ – reference API
description: Kreslí spline pomocí zadaného pera.
type: docs
weight: 794
url: /cs/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) method

Kreslí spline pomocí zadaného pera.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) bodů, které určují spline |
| tension | **float** | Hodnota, která určuje napětí spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) method

Kreslí spline pomocí zadaného pera.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) bodů, které určují spline |
| tension | **float** | Hodnota, která určuje napětí spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) method

Kreslí spline pomocí zadaného pera.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) bodů, které určují spline |
| offset | **int32_t** | Posun od 1. prvku v poli **points** |
| numberOfSegments | **int32_t** | Počet segmentů, které mají být zahrnuty do křivky |
| tension | **float** | Hodnota, která určuje napětí spline |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) method

Kreslí spline pomocí zadaného pera.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) bodů, které určují spline |
| offset | **int32_t** | Posun od 1. prvku v poli **points** |
| numberOfSegments | **int32_t** | Počet segmentů, které mají být zahrnuty do křivky |
| tension | **float** | Hodnota, která určuje napětí spline |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Pen](../../pen/)
* Třída [Point](../../point/)
* Třída [Graphics](../)
* Třída [PointF](../../pointf/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)