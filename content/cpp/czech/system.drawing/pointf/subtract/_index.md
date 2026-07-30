---
title: Subtract()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odečte hodnoty šířky a výšky zadaného objektu SizeF od hodnot souřadnic X a Y zadaného objektu PointF.
type: docs
weight: 157
url: /cs/system.drawing/pointf/subtract/
---
## PointF::Subtract(const PointF\&, const SizeF\&) metoda

Odečte hodnoty šířky a výšky zadaného objektu [SizeF](../../sizef/) od souřadnic X a Y zadaného objektu [PointF](../).

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const SizeF &size)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| point | const [PointF](../)\& | Bod, který se má posunout |
| size | const [SizeF](../../sizef/)\& | Objekt [SizeF](../../sizef/), který určuje hodnoty, které se odečtou od souřadnic **point** |

### Návratová hodnota

Nový objekt [PointF](../), jehož hodnota souřadnice X je rovna výsledku odečtení hodnoty šířky **size** od hodnoty souřadnice X **point** a hodnota souřadnice Y je rovna výsledku odečtení hodnoty výšky **size** od hodnoty souřadnice Y **point**.

## PointF::Subtract(const PointF\&, const Size\&) metoda

Odečte hodnoty šířky a výšky zadaného objektu [Size](../../size/) od souřadnic X a Y zadaného objektu [PointF](../).

```cpp
static PointF System::Drawing::PointF::Subtract(const PointF &point, const Size &size)
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| point | const [PointF](../)\& | Bod, který se má posunout |
| size | const [Size](../../size/)\& | Objekt [Size](../../size/), který určuje hodnoty, které se odečtou od souřadnic **point** |

### Návratová hodnota

Nový objekt [PointF](../), jehož hodnota souřadnice X je rovna výsledku odečtení hodnoty šířky **size** od hodnoty souřadnice X **point** a hodnota souřadnice Y je rovna výsledku odečtení hodnoty výšky **size** od hodnoty souřadnice Y **point**.

## Viz také

* Třída [PointF](../)
* Třída [SizeF](../../sizef/)
* Třída [Size](../../size/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)