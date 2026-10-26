---
title: Inflate()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het huidige object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de opgegeven hoeveelheden.
type: docs
weight: 261
url: /nl/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) methode

Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het huidige object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de opgegeven hoeveelheden.

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | int | The amount by which the width of the rectangle is to be increased in both directions |
| height | int | The amount by which the height of the rectangle is to be increased in both directions |

## Rectangle::Inflate(const Size\&) methode

Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het huidige object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de hoeveelheden die zijn gespecificeerd door breedte- en hoogte-waarden van het opgegeven size-object overeenkomstig.

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | const [Size](../../size/)\& | The [Size](../../size/) object specifying the amounts to increase the width and height of the rectangle by |

## Rectangle::Inflate(const Rectangle\&, int, int) methode

Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het opgegeven object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de opgegeven hoeveelheden.

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | A rectangle to inflate |
| x | int | The amount by which the width of the rectangle is to be increased in both directions |
| y | int | The amount by which the height of the rectangle is to be increased in both directions |

### Retourwaarde

Het [Rectangle](../) object dat de vergrote rechthoek vertegenwoordigt

## Zie ook

* Klasse [Rectangle](../)
* Klasse [Size](../../size/)
* Namespace [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)