---
title: Rectangle
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een rechthoekig gebied van een afbeelding voor, gedefinieerd door gehele X- en Y-coördinaten van de linkerbovenhoek en de breedte en hoogte. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 235
url: /nl/system.drawing/rectangle/
---
## Rectangle klasse

Stelt een rechthoekig gebied van een afbeelding voor, gedefinieerd door gehele X- en Y-coördinaten van de linkerbovenhoek en de breedte en hoogte. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Rectangle
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Construeert een [Rectangle](./) object van het opgegeven [RectangleF](../rectanglef/) object door de locatie- en groottewaarden van het [RectangleF](../rectanglef/) object af te ronden naar de eerstvolgende hogere gehele getallen. |
| **bool** [Contains](./contains/)(int, int) const | Bepaalt of het opgegeven punt zich binnen de rechthoek bevindt die door het huidige object wordt vertegenwoordigd. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Bepaalt of het opgegeven punt zich binnen de rechthoek bevindt die door het huidige object wordt vertegenwoordigd. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Bepaalt of de opgegeven rechthoek zich binnen de rechthoek bevindt die door het huidige object wordt vertegenwoordigd. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Bepaalt of de rechthoeken die door het huidige en het opgegeven object worden weergegeven identiek zijn. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Construeert een nieuw [Rectangle](./) object dat een rechthoek vertegenwoordigt met de opgegeven randlocaties. |
| int [get_Bottom](./get_bottom/)() const | Geeft de y-coördinaat van de onderkant van de rechthoek terug die door het huidige object wordt weergegeven. |
| int [get_Height](./get_height/)() const | Geeft de hoogte van de rechthoek terug die door het huidige object wordt weergegeven. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bepaalt of X- en Y-coördinaten van de linkerbovenhoek van de rechthoek die door het huidige object wordt weergegeven, evenals de breedte en hoogte, de waarde 0 hebben. |
| int [get_Left](./get_left/)() const | Geeft de X-coördinaat van de linkerrand van de rechthoek terug die door het huidige object wordt weergegeven. |
| [Point](../point/) [get_Location](./get_location/)() const | Retourneert een instantie van de [Point](../point/) klasse die de locatie van de linkerbovenhoek van de rechthoek specificeert die door het huidige object wordt weergegeven. |
| int [get_Right](./get_right/)() const | Geeft de X-coördinaat van de rechterrand van de rechthoek terug die door het huidige object wordt weergegeven. |
| [Size](../size/) [get_Size](./get_size/)() const | Retourneert een instantie van de [Size](../size/) klasse die de breedte en hoogte van de rechthoek specificeert die door het huidige object wordt weergegeven. |
| int [get_Top](./get_top/)() const | Geeft de Y-coördinaat van de bovenrand van de rechthoek terug die door het huidige object wordt weergegeven. |
| int [get_Width](./get_width/)() const | Geeft de breedte van de rechthoek terug die door het huidige object wordt weergegeven. |
| int [get_X](./get_x/)() const | Geeft de X-coördinaat van de linkerbovenhoek van de rechthoek terug die door het huidige object wordt weergegeven. |
| int [get_Y](./get_y/)() const | Geeft de Y-coördinaat van de linkerbovenhoek van de rechthoek terug die door het huidige object wordt weergegeven. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode van het huidige object. |
| void [Inflate](./inflate/)(int, int) | Vergroot de breedte en hoogte van de rechthoek die door het huidige object wordt weergegeven, waarbij de locatie van het geometrisch centrum behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de opgegeven waarden. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Vergroot de breedte en hoogte van de rechthoek die door het huidige object wordt weergegeven, waarbij de locatie van het geometrisch centrum behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de waarden die door de breedte- en hoogte-eigenschappen van het opgegeven grootte-object worden gespecificeerd. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Vergroot de breedte en hoogte van de rechthoek die door het opgegeven object wordt weergegeven, waarbij de locatie van het geometrisch centrum behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de opgegeven waarden. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Vervangt de rechthoek die door het huidige object wordt weergegeven door de rechthoek die ontstaat uit de intersectie ervan met de rechthoek die door het opgegeven object wordt weergegeven. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Retourneert een rechthoek die het resultaat is van de intersectie van de opgegeven rechthoeken. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Bepaalt of de rechthoeken die door het huidige en het opgegeven object worden weergegeven, elkaar overlappen. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Verplaatst de positie van de rechthoek die door het huidige object wordt weergegeven met de opgegeven waarden. |
| void [Offset](./offset/)(int, int) | Verplaatst de positie van de rechthoek die door het huidige object wordt weergegeven met de opgegeven waarden. |
| [operator RectangleF](./operator_rectanglef/)() const | Retourneert een [RectangleF](../rectanglef/) object dat een rechthoek vertegenwoordigt die gelijk is aan de rechthoek die door het huidige object wordt weergegeven. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Retourneert altijd waar. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Retourneert altijd onwaar. |
| [Rectangle](./rectangle/)() | Construeert een nieuw exemplaar van [Rectangle](./) object dat een rechthoek vertegenwoordigt met X- en Y-coördinaten en breedte- en hoogte-waarden ingesteld op 0. |
| [Rectangle](./rectangle/)(int, int, int, int) | Construeert een nieuw exemplaar van [Rectangle](./) object dat een rechthoek vertegenwoordigt met de opgegeven coördinaten van de linkerbovenhoek en breedte en hoogte. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Construeert een nieuw exemplaar van [Rectangle](./) object dat een rechthoek vertegenwoordigt met de coördinaten van de linkerbovenhoek gespecificeerd als een instantie van [Point](../point/) klasse en de breedte en hoogte gespecificeerd als een instantie van [Size](../size/) klasse. |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Construeert een nieuw exemplaar van [Rectangle](./) object dat de rechthoek vertegenwoordigt die gelijk is aan de opgegeven. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Construeert een [Rectangle](./) object van het opgegeven [RectangleF](../rectanglef/) object door de locatie- en groottewaarden van het [RectangleF](../rectanglef/) object af te ronden op het dichtstbijzijnde gehele getal. |
| void [set_Height](./set_height/)(int) | Stelt de hoogte van de rechthoek in die door het huidige object wordt weergegeven. |
| void [set_Location](./set_location/)([Point](../point/)) | Stelt de locatie van de linkerbovenhoek van de rechthoek in die door het huidige object wordt weergegeven. |
| void [set_Size](./set_size/)([Size](../size/)) | Stelt de breedte en hoogte van de rechthoek in die door het huidige object wordt weergegeven. |
| void [set_Width](./set_width/)(int) | Stelt de breedte van de rechthoek in die door het huidige object wordt weergegeven. |
| void [set_X](./set_x/)(int) | Stelt de X-coördinaat van de linkerbovenhoek van de rechthoek in die door het huidige object wordt weergegeven. |
| void [set_Y](./set_y/)(int) | Stelt de Y-coördinaat van de linkerbovenhoek van de rechthoek in die door het huidige object wordt weergegeven. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retourneert de stringrepresentatie van het huidige object. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Construeert een [Rectangle](./) object van het opgegeven [RectangleF](../rectanglef/) object door de locatie- en groottewaarden van het [RectangleF](../rectanglef/) object af te kappen op het eerstvolgende lagere gehele getal. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Retourneert een rechthoek die het resultaat is van de unie van de opgegeven rechthoeken. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Empty](./empty/) | Een lege rechthoek, d.w.z. een rechthoek waarvan de locatie- en groottewaarden nul zijn. |

## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)