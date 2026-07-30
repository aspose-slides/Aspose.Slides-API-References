---
title: Subtract()
second_title: Aspose.Slides pro C++ API Reference
description: Odečte hodnoty šířky a výšky zadaného objektu Size od hodnot souřadnic X a Y zadaného objektu Point odpovídajícím způsobem.
type: docs
weight: 196
url: /cs/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) metoda

Odečte hodnoty šířky a výšky zadaného objektu [Size](../../size/) od hodnot souřadnic X a Y zadaného objektu [Point](../) odpovídajícím způsobem.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| point | const [Point](../)\& | Bod k překladu |
| size | const [Size](../../size/)\& | Objekt [Size](../../size/), který určuje hodnoty, které mají být odečteny od hodnot souřadnic **point** |

### Návratová hodnota

Nový objekt [Point](../), jehož hodnota souřadnice X je rovna výsledku odečtení hodnoty šířky **size** od hodnoty souřadnice X **point** a hodnota souřadnice Y je rovna výsledku odečtení hodnoty výšky **size** od hodnoty souřadnice Y **point**.

## Viz také

* Třída [Point](../)
* Třída [Size](../../size/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)