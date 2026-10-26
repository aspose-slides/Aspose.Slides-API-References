---
title: FillPolygon()
second_title: Aspose.Slides für C++ API-Referenz
description: Füllt die Innenbereiche des angegebenen Polygons mit dem angegebenen Pinsel.
type: docs
weight: 417
url: /de/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) method


Füllt die Innenbereiche des angegebenen Polygons mit dem angegebenen Pinsel.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein [Brush](../../brush/)-Objekt, das die Parameter der Füllung angibt |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Ein Array, das die Punkte enthält, die das Polygon definieren |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Der Füllmodus |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) method


Füllt die Innenbereiche des angegebenen Polygons mit dem angegebenen Pinsel.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Ein [Brush](../../brush/)-Objekt, das die Parameter der Füllung angibt |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Ein Array, das die Punkte enthält, die das Polygon definieren |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Der Füllmodus |

## Siehe auch

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Brush](../../brush/)
* Klasse [Point](../../point/)
* Klasse [Graphics](../)
* Klasse [PointF](../../pointf/)
* Namensraum [System::Drawing](../../)
* Library [Aspose.Slides](../../../)