---
title: DrawClosedCurve()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Rysuje zamkniętą krzywą spline przy użyciu określonego pióra.
type: docs
weight: 781
url: /pl/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) metoda

Rysuje zamkniętą krzywą spline przy użyciu określonego pióra.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane przy rysowaniu krzywej spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) punktów, które określają krzywą spline |
| tension | **float** | Wartość określająca napięcie krzywej spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) metoda

Rysuje zamkniętą krzywą spline przy użyciu określonego pióra.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | Pióro używane przy rysowaniu krzywej spline |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) punktów, które określają krzywą spline |
| tension | **float** | Wartość określająca napięcie krzywej spline |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |

## Zobacz także

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Pen](../../pen/)
* Klasa [Point](../../point/)
* Klasa [Graphics](../)
* Klasa [PointF](../../pointf/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)