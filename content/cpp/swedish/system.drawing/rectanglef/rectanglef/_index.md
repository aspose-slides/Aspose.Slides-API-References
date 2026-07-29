---
title: RectangleF()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av RectangleF-objektet som representerar en rektangel med X- och Y-koordinater samt bredd- och höjdvärden satta till 0.
type: docs
weight: 1
url: /sv/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() konstruktor


Skapar en ny instans av [RectangleF](../)-objektet som representerar en rektangel med X- och Y-koordinater samt bredd- och höjdvärden satta till 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) konstruktor


Skapar en ny instans av [RectangleF](../)-objektet som representerar en rektangel med de angivna koordinaterna för dess övre vänstra hörn samt bredd och höjd.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | Ett värde för X-koordinaten för rektangelns övre vänstra hörn |
| y | **float** | Ett värde för Y-koordinaten för rektangelns övre vänstra hörn |
| width | **float** | Rektangelns bredd |
| height | **float** | Rektangelns höjd |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) konstruktor


Skapar en ny instans av [RectangleF](../)-objektet som representerar en rektangel där koordinaterna för dess övre vänstra hörn anges som en instans av klassen [PointF](../../pointf/) och dess bredd och höjd som en instans av klassen [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Specificerar platsen för rektangelns övre vänstra hörn |
| size | const [SizeF](../../sizef/)\& | Specificerar rektangelns bredd och höjd |

## RectangleF::RectangleF(const Rectangle\&) konstruktor


Skapar en ny instans av [RectangleF](../)-objektet som representerar den rektangel som är ekvivalent med den angivna.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | En instans av klassen [Rectangle](../../rectangle/) som specificerar positionen och storleken på den rektangel som ska representeras av det objekt som konstrueras |

## Se även

* Klass [RectangleF](../)
* Klass [PointF](../../pointf/)
* Klass [SizeF](../../sizef/)
* Klass [Rectangle](../../rectangle/)
* Namnrymd [System::Drawing](../../)
* Bibliotek [Aspose.Slides](../../../)