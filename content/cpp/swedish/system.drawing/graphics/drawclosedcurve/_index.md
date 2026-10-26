---
title: DrawClosedCurve()
second_title: Aspose.Slides för C++ API-referens
description: Ritar en sluten spline med den angivna pennan.
type: docs
weight: 781
url: /sv/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) metod


Ritar en sluten spline med den angivna pennan.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En penna att använda när splinen ritas |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) av punkter som bestämmer splinen |
| tension | **float** | Värde som anger spänningen på splinen |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) metod


Ritar en sluten spline med den angivna pennan.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | En penna att använda när splinen ritas |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) av punkter som bestämmer splinen |
| tension | **float** | Värde som anger spänningen på splinen |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |

## Se även

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Pen](../../pen/)
* Klass [Point](../../point/)
* Klass [Graphics](../)
* Klass [PointF](../../pointf/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)