---
title: Add()
second_title: Aspose.Slides pro C++ – dokumentace API
description: Přidá šířku a výšku zadaného objektu SizeF k hodnotám souřadnic X a Y zadaného objektu PointF odpovídajícím způsobem.
type: docs
weight: 144
url: /cs/system.drawing/pointf/add/
---
## PointF::Add(const PointF\&, const SizeF\&) metoda

Přidá šířku a výšku zadaného objektu [SizeF](../../sizef/) k hodnotám souřadnic X a Y zadaného objektu [PointF](../) odpovídajícím způsobem.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const SizeF &size)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| point | const [PointF](../)\& | Bod k překladu |
| size | const [SizeF](../../sizef/)\& | Objekt [SizeF](../../sizef/), který určuje hodnoty, které se mají přidat k hodnotám souřadnic **point** |

### Návratová hodnota

Nový objekt [PointF](../), jehož hodnota souřadnice X je rovna součtu hodnoty souřadnice X **point** a šířky **size** a hodnota souřadnice Y je rovna součtu hodnoty souřadnice Y **point** a výšky **size**

## PointF::Add(const PointF\&, const Size\&) metoda

Přidá šířku a výšku zadaného objektu [Size](../../size/) k hodnotám souřadnic X a Y zadaného objektu [PointF](../) odpovídajícím způsobem.

```cpp
static PointF System::Drawing::PointF::Add(const PointF &point, const Size &size)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| point | const [PointF](../)\& | Bod k překladu |
| size | const [Size](../../size/)\& | Objekt [Size](../../size/), který určuje hodnoty, které se mají přidat k hodnotám souřadnic **point** |

### Návratová hodnota

Nový objekt [PointF](../), jehož hodnota souřadnice X je rovna součtu hodnoty souřadnice X **point** a šířky **size** a hodnota souřadnice Y je rovna součtu hodnoty souřadnice Y **point** a výšky **size**

## Viz také

* Třída [PointF](../)
* Třída [SizeF](../../sizef/)
* Třída [Size](../../size/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)