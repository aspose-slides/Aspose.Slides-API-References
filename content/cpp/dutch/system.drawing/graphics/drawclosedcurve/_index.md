---
title: DrawClosedCurve()
second_title: Aspose.Slides voor C++ API-referentie
description: Tekent een gesloten spline met de opgegeven pen.
type: docs
weight: 781
url: /nl/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) methode


Tekent een gesloten spline met de opgegeven pen.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Een pen die wordt gebruikt bij het tekenen van de spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) van punten die de spline bepalen |
| tension | **float** | Waarde die de spanning van de spline aangeeft |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | genegeerd |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) methode


Tekent een gesloten spline met de opgegeven pen.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Een pen die wordt gebruikt bij het tekenen van de spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) van punten die de spline bepalen |
| tension | **float** | Waarde die de spanning van de spline aangeeft |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | genegeerd |

## Zie ook

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Pen](../../pen/)
* Klasse [Point](../../point/)
* Klasse [Graphics](../)
* Klasse [PointF](../../pointf/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)