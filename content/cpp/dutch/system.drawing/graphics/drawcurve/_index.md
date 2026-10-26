---
title: DrawCurve()
second_title: Aspose.Slides voor C++ API-referentie
description: Tekent een spline met de opgegeven pen.
type: docs
weight: 794
url: /nl/system.drawing/graphics/drawcurve/
---
## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float) methode


Tekent een spline met de opgegeven pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Een pen die wordt gebruikt bij het tekenen van de spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) van punten die de spline bepalen |
| tension | **float** | Waarde die de spanning van de spline specificeert |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float) methode


Tekent een spline met de opgegeven pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Een pen die wordt gebruikt bij het tekenen van de spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) van punten die de spline bepalen |
| tension | **float** | Waarde die de spanning van de spline specificeert |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, int32_t, int32_t, float) methode


Tekent een spline met de opgegeven pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Een pen die wordt gebruikt bij het tekenen van de spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) van punten die de spline bepalen |
| offset | **int32_t** | Offset vanaf het eerste element in de **points** array |
| numberOfSegments | **int32_t** | Aantal segmenten die in de curve moeten worden opgenomen |
| tension | **float** | Waarde die de spanning van de spline specificeert |

## Graphics::DrawCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, int32_t, int32_t, float) methode


Tekent een spline met de opgegeven pen.

```cpp
void System::Drawing::Graphics::DrawCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, int32_t offset, int32_t numberOfSegments, float tension=0.5f)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Een pen die wordt gebruikt bij het tekenen van de spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) van punten die de spline bepalen |
| offset | **int32_t** | Offset vanaf het eerste element in de **points** array |
| numberOfSegments | **int32_t** | Aantal segmenten die in de curve moeten worden opgenomen |
| tension | **float** | Waarde die de spanning van de spline specificeert |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Pen](../../pen/)
* Klasse [Point](../../point/)
* Klasse [Graphics](../)
* Klasse [PointF](../../pointf/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)