---
title: Inflate()
second_title: Aspose.Slides voor C++ API-referentie
description: Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het huidige object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen met de opgegeven hoeveelheden vergroot.
type: docs
weight: 261
url: /nl/system.drawing/rectanglef/inflate/
---
## RectangleF::Inflate(float, float) methode

Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het huidige object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen met de opgegeven hoeveelheden vergroot.

```cpp
void System::Drawing::RectangleF::Inflate(float width, float height)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | **float** | De hoeveelheid waarmee de breedte van de rechthoek in beide richtingen moet worden vergroot |
| height | **float** | De hoeveelheid waarmee de hoogte van de rechthoek in beide richtingen moet worden vergroot |

## RectangleF::Inflate(const SizeF\&) methode

Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het huidige object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de hoeveelheden die worden opgegeven door de breedte- en hoogtewaarden van het opgegeven size-object.

```cpp
void System::Drawing::RectangleF::Inflate(const SizeF &size)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| size | const [SizeF](../../sizef/)\& | Het [SizeF](../../sizef/)-object dat de bedragen specificeert waarmee de breedte en hoogte van de rechthoek moeten worden vergroot |

## RectangleF::Inflate(const RectangleF\&, float, float) methode

Vergroot de breedte en hoogte van de rechthoek die wordt weergegeven door het opgegeven object, waarbij de locatie van het geometrische middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen met de opgegeven hoeveelheden vergroot.

```cpp
static RectangleF System::Drawing::RectangleF::Inflate(const RectangleF &rect, float x, float y)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | Een rechthoek die moet worden vergroot |
| x | **float** | De hoeveelheid waarmee de breedte van de rechthoek in beide richtingen moet worden vergroot |
| y | **float** | De hoeveelheid waarmee de hoogte van de rechthoek in beide richtingen moet worden vergroot |

### Retourwaarde

Het [RectangleF](../) object dat de vergrote rechthoek vertegenwoordigt

## Zie ook

* Klasse [RectangleF](../)
* Klasse [SizeF](../../sizef/)
* Naamruimte [System::Drawing](../../)
* Bibliotheek [Aspose.Slides](../../../)