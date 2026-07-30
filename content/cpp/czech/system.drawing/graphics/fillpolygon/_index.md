---
title: FillPolygon()
second_title: Aspose.Slides pro C++ – Referenční příručka API
description: Vyplní vnitřní oblasti zadaného polygonu pomocí určeného štětce.
type: docs
weight: 417
url: /cs/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) metoda

Vyplní vnitřní oblasti určeného polygonu pomocí zadaného štětce.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objekt [Brush](../../brush/), který určuje parametry výplně |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Pole obsahující body, které definují polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Režim výplně |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) metoda

Vyplní vnitřní oblasti určeného polygonu pomocí zadaného štětce.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objekt [Brush](../../brush/), který určuje parametry výplně |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Pole obsahující body, které definují polygon |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Režim výplně |

## Viz také

* Výčet [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [Brush](../../brush/)
* Třída [Point](../../point/)
* Třída [Graphics](../)
* Třída [PointF](../../pointf/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)