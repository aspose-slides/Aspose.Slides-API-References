---
title: RectangleF()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van het RectangleF object dat een rechthoek voorstelt met X- en Y-coördinaten en breedte- en hoogte-waarden ingesteld op 0.
type: docs
weight: 1
url: /nl/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() constructor

Construeert een nieuw exemplaar van [RectangleF](../) object dat een rechthoek voorstelt met X- en Y-coördinaten en breedte- en hoogte-waarden ingesteld op 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) constructor

Construeert een nieuw exemplaar van [RectangleF](../) object dat een rechthoek voorstelt met de opgegeven coördinaten van de linkerbovenhoek en breedte en hoogte.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | Een waarde van de X-coördinaat van de linkerbovenhoek van de rechthoek |
| y | **float** | Een waarde van de Y-coördinaat van de linkerbovenhoek van de rechthoek |
| width | **float** | De breedte van de rechthoek |
| height | **float** | De hoogte van de rechthoek |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) constructor

Construeert een nieuw exemplaar van [RectangleF](../) object dat een rechthoek voorstelt met de coördinaten van de linkerbovenhoek opgegeven als een exemplaar van de [PointF](../../pointf/) klasse en de breedte en hoogte als een exemplaar van de [SizeF](../../sizef/) klasse.

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | Geeft de locatie van de linkerbovenhoek van de rechthoek aan |
| size | const [SizeF](../../sizef/)\& | Geeft de breedte en hoogte van de rechthoek aan |

## RectangleF::RectangleF(const Rectangle\&) constructor

Construeert een nieuw exemplaar van [RectangleF](../) object dat de rechthoek equivalent aan de opgegeven representeert.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Een exemplaar van de [Rectangle](../../rectangle/) klasse die de positie en grootte van de rechthoek specificeert die door het te construeren object wordt weergegeven |

## Zie ook

* Klasse [RectangleF](../)
* Klasse [PointF](../../pointf/)
* Klasse [SizeF](../../sizef/)
* Klasse [Rectangle](../../rectangle/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)