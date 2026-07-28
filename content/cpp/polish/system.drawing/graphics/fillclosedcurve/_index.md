---
title: FillClosedCurve()
second_title: Referencja API Aspose.Slides dla C++
description: Rysuje zamkniętą krzywą typu spline przy użyciu określonego pędzla.
type: docs
weight: 807
url: /pl/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) metoda

Rysuje zamkniętą krzywą typu spline przy użyciu określonego pędzla.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Pędzel używany przy rysowaniu krzywej |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) punktów określających krzywą |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNOROWANE |
| tension | **float** | Wartość określająca napięcie krzywej |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) metoda

Rysuje zamkniętą krzywą typu spline przy użyciu określonego pędzla.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Pędzel używany przy rysowaniu krzywej |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) punktów określających krzywą |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNOROWANE |
| tension | **float** | Wartość określająca napięcie krzywej |

## Zobacz także

* Wyliczenie [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [Brush](../../brush/)
* Klasa [PointF](../../pointf/)
* Klasa [Graphics](../)
* Klasa [Point](../../point/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)