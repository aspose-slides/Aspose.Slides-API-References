---
title: FillPolygon()
second_title: Aspose.Slides dla C++ - referencja API
description: Wypełnia wnętrza określonego wielokąta przy użyciu podanego pędzla.
type: docs
weight: 417
url: /pl/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) metoda

Wypełnia wnętrza określonego wielokąta przy użyciu podanego pędzla.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Obiekt [Brush](../../brush/) określający parametry wypełnienia |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Tablica zawierająca punkty definiujące wielokąt |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Tryb wypełnienia |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) metoda

Wypełnia wnętrza określonego wielokąta przy użyciu podanego pędzla.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Obiekt [Brush](../../brush/) określający parametry wypełnienia |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Tablica zawierająca punkty definiujące wielokąt |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | Tryb wypełnienia |

## Zobacz także

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [Brush](../../brush/)
* Klasa [Point](../../point/)
* Klasa [Graphics](../)
* Klasa [PointF](../../pointf/)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)