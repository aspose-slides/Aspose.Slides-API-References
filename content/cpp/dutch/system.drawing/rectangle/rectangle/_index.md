---
title: Rectangle()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van het Rectangle object dat een rechthoek voorstelt met X en Y coördinaten en breedte en hoogte waarden ingesteld op 0.
type: docs
weight: 1
url: /nl/system.drawing/rectangle/rectangle/
---
## Rectangle::Rectangle() constructor

Construeert een nieuw exemplaar van [Rectangle](../) object dat een rechthoek voorstelt met X- en Y-coördinaten en breedte- en hoogtewaarden ingesteld op 0.

```cpp
System::Drawing::Rectangle::Rectangle()
```

## Rectangle::Rectangle(int, int, int, int) constructor

Construeert een nieuw exemplaar van [Rectangle](../) object dat een rechthoek voorstelt met de opgegeven coördinaten van de linkerbovenhoek en breedte en hoogte.

```cpp
System::Drawing::Rectangle::Rectangle(int x, int y, int width, int height)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| x | int | Een waarde van de X-coördinaat van de linkerbovenhoek van de rechthoek |
| y | int | Een waarde van de Y-coördinaat van de linkerbovenhoek van de rechthoek |
| width | int | De breedte van de rechthoek |
| height | int | De hoogte van de rechthoek |

## Rectangle::Rectangle(const Point\&, const Size\&) constructor

Construeert een nieuw exemplaar van [Rectangle](../) object dat een rechthoek voorstelt met de coördinaten van de linkerbovenhoek gespecificeerd als een exemplaar van de [Point](../../point/) klasse en de breedte en hoogte als een exemplaar van de [Size](../../size/) klasse.

```cpp
System::Drawing::Rectangle::Rectangle(const Point &location, const Size &size)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| location | const [Point](../../point/)\& | Specificeert de locatie van de linkerbovenhoek van de rechthoek |
| size | const [Size](../../size/)\& | Specificeert de breedte en hoogte van de rechthoek |

## Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_\&) constructor

Construeert een nieuw exemplaar van [Rectangle](../) object dat de rechthoek vertegenwoordigt die gelijk is aan de opgegeven.

```cpp
System::Drawing::Rectangle::Rectangle(const System::Windows::Forms::Screen::Rectangle_ &rect)
```

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| rect | const **System::Windows::Forms::Screen::Rectangle_**\& | Een exemplaar van de **System::Windows::Forms::Screen::Rectangle_** klasse die de positie en grootte van de rechthoek opgeeft die wordt vertegenwoordigd door het object dat wordt geconstrueerd |

## Zie ook

* Klasse [Rectangle](../)
* Klasse [Point](../../point/)
* Klasse [Size](../../size/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)