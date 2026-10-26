---
title: FillPolygon()
second_title: Riferimento API di Aspose.Slides per C++
description: Riempie gli interni del poligono specificato usando il pennello specificato.
type: docs
weight: 417
url: /it/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) metodo


Riempie gli interni del poligono specificato usando il pennello specificato.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un oggetto [Brush](../../brush/) che specifica i parametri del riempimento |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Un array contenente i punti che definiscono il poligono |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | La modalità di riempimento |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) metodo


Riempie gli interni del poligono specificato usando il pennello specificato.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un oggetto [Brush](../../brush/) che specifica i parametri del riempimento |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Un array contenente i punti che definiscono il poligono |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | La modalità di riempimento |

## Vedi anche

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)