---
title: FillPolygon()
second_title: Referencia de API de Aspose.Slides para C++
description: Rellena los interiores del polígono especificado usando el pincel especificado.
type: docs
weight: 417
url: /es/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) método

Rellena los interiores del polígono especificado usando el pincel especificado.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objeto [Brush](../../brush/) que especifica los parámetros del relleno |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Una matriz que contiene los puntos que definen el polígono |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | El modo de relleno |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) método

Rellena los interiores del polígono especificado usando el pincel especificado.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Un objeto [Brush](../../brush/) que especifica los parámetros del relleno |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Una matriz que contiene los puntos que definen el polígono |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | El modo de relleno |

## Ver también

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)