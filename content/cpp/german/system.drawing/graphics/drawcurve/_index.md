---
title: DrawCurve()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeichnet einen Spline mit dem angegebenen Stift.
type: docs
weight: 794
url: /de/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) Methode

Zeichnet einen Spline mit dem angegebenen Stift.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Splines verwendet wird |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) von Punkten, die den Spline bestimmen |
| tension | **float** | Wert, der die Spannung des Splines angibt |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) Methode

Zeichnet einen Spline mit dem angegebenen Stift.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Splines verwendet wird |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) von Punkten, die den Spline bestimmen |
| tension | **float** | Wert, der die Spannung des Splines angibt |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) Methode

Zeichnet einen Spline mit dem angegebenen Stift.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Splines verwendet wird |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) von Punkten, die den Spline bestimmen |
| offset | **int32_t** | Versatz vom ersten Element im **points**-Array |
| numberOfSegments | **int32_t** | Anzahl der Segmente, die in die Kurve aufgenommen werden |
| tension | **float** | Wert, der die Spannung des Splines angibt |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) Methode

Zeichnet einen Spline mit dem angegebenen Stift.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Ein Stift, der beim Zeichnen des Splines verwendet wird |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) von Punkten, die den Spline bestimmen |
| offset | **int32_t** | Versatz vom ersten Element im **points**-Array |
| numberOfSegments | **int32_t** | Anzahl der Segmente, die in die Kurve aufgenommen werden |
| tension | **float** | Wert, der die Spannung des Splines angibt |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Pen](../../pen/)
* Klasse [Point](../../point/)
* Klasse [Graphics](../)
* Klasse [PointF](../../pointf/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)