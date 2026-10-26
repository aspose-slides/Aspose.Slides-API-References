---
title: RectangleF()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci objektu RectangleF, který představuje obdélník se souřadnicemi X a Y a hodnotami šířky a výšky nastavenými na 0.
type: docs
weight: 1
url: /cs/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() konstruktor

Vytvoří novou instanci objektu [RectangleF](../), který představuje obdélník se souřadnicemi X a Y a hodnotami šířky a výšky nastavenými na 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) konstruktor

Vytvoří novou instanci objektu [RectangleF](../), který představuje obdélník se zadanými souřadnicemi levého horního rohu a šířkou a výškou.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| x | **float** | Hodnota souřadnice X levého horního rohu obdélníku |
| y | **float** | Hodnota souřadnice Y levého horního rohu obdélníku |
| width | **float** | Šířka obdélníku |
| height | **float** | Výška obdélníku |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) konstruktor

Vytvoří novou instanci objektu [RectangleF](../), který představuje obdélník, jehož souřadnice levého horního rohu jsou určeny jako instance třídy [PointF](../../pointf/) a jeho šířka a výška jako instance třídy [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Určuje umístění levého horního rohu obdélníku |
| size | const [SizeF](../../sizef/)\& | Určuje šířku a výšku obdélníku |

## RectangleF::RectangleF(const Rectangle\&) konstruktor

Vytvoří novou instanci objektu [RectangleF](../), který představuje obdélník ekvivalentní zadanému.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Instance třídy [Rectangle](../../rectangle/), která určuje polohu a velikost obdélníku, který bude reprezentován vytvářeným objektem |

## Viz také

* Třída [RectangleF](../)
* Třída [PointF](../../pointf/)
* Třída [SizeF](../../sizef/)
* Třída [Rectangle](../../rectangle/)
* Jmenný prostor [System::Drawing](../../)
* Knihovna [Aspose.Slides](../../../)