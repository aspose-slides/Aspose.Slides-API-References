---
title: DrawClosedCurve()
second_title: Aspose.Slides pro C++ API Reference
description: Vykreslí uzavřenou křivku pomocí zadaného pera.
type: docs
weight: 781
url: /cs/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) metoda

Vykreslí uzavřenou křivku pomocí zadaného pera.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení křivky |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) bodů, který určuje křivku |
| tension | **float** | Hodnota, která určuje napětí křivky |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNOROVÁNO |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) metoda

Vykreslí uzavřenou křivku pomocí zadaného pera.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pero, které se použije při kreslení křivky |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) bodů, který určuje křivku |
| tension | **float** | Hodnota, která určuje napětí křivky |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNOROVÁNO |

## Viz také

* Výčet [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Pen](../../pen/)
* Třída [Point](../../point/)
* Třída [Graphics](../)
* Třída [PointF](../../pointf/)
* Prostor názvů [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)