---
title: FillPolygon()
second_title: Aspose.Slides för C++ API-referens
description: Fyller insidan av den angivna polygonen med den angivna penseln.
type: docs
weight: 417
url: /sv/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) metod

Fyller insidan av den angivna polygonen med den angivna penseln.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) metod

Fyller insidan av den angivna polygonen med den angivna penseln.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) object that specifies the parameters of the fill |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | An array containing the points that define the polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | The fill mode |

## Se även

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Brush](../../brush/)
* Klass [Point](../../point/)
* Klass [Graphics](../)
* Klass [PointF](../../pointf/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)