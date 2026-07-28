---
title: FillPolygon()
second_title: Aspose.Slides for C++ API Referencia
description: Kitölti a megadott sokszög belsejét a megadott ecset segítségével.
type: docs
weight: 417
url: /hu/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) metódus


Kitölti a megadott sokszög belsejét a megadott ecset segítségével.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) objektum, amely meghatározza a kitöltés paramétereit |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Egy tömb, amely a sokszög pontjait tartalmazza |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | A kitöltési mód |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) metódus


Kitölti a megadott sokszög belsejét a megadott ecset segítségével.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | A [Brush](../../brush/) objektum, amely meghatározza a kitöltés paramétereit |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Egy tömb, amely a sokszög pontjait tartalmazza |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | A kitöltési mód |

## Lásd még

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Brush](../../brush/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)