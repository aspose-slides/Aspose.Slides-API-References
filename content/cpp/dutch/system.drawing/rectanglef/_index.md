---
title: RectangleF
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een rechthoekig gebied van een afbeelding voor, gedefinieerd door enkelprecisie drijvende-komma X en Y coördinaten van de linkerbovenhoek en de breedte en hoogte. Dit type moet op de stack worden gealloceerd en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 248
url: /nl/system.drawing/rectanglef/
---
## RectangleF klasse

Stelt een rechthoekig gebied van een afbeelding voor, gedefinieerd door enkelprecisie drijvende-komma X- en Y-coördinaten van de linkerbovenhoek en de breedte en hoogte. Dit type dient op de stack te worden gealloceerd en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
class RectangleF
```

## Methoden

| Method | Description |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Bepaalt of het opgegeven punt zich binnen de rechthoek bevindt die door het huidige object wordt weergegeven. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Bepaalt of het opgegeven punt zich binnen de rechthoek bevindt die door het huidige object wordt weergegeven. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Bepaalt of de opgegeven rechthoek zich binnen de rechthoek bevindt die door het huidige object wordt weergegeven. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Bepaalt of de rechthoeken die door het huidige en het opgegeven object worden weergegeven identiek zijn. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Construeert een nieuw [RectangleF](./) object dat een rechthoek vertegenwoordigt met de opgegeven randlocaties. |
| **float** [get_Bottom](./get_bottom/)() const | Retourneert de y-coördinaat van de onderrand van de rechthoek die door het huidige object wordt weergegeven. |
| **float** [get_Height](./get_height/)() const | Retourneert de hoogte van de rechthoek die door het huidige object wordt weergegeven. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bepaalt of X- en Y-coördinaten van de linkerbovenhoek van de rechthoek, evenals de breedte en hoogte, de waarde 0 hebben. |
| **float** [get_Left](./get_left/)() const | Retourneert de X-coördinaat van de linkerrand van de rechthoek die door het huidige object wordt weergegeven. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Retourneert een instantie van de [PointF](../pointf/) klasse die de locatie van de linkerbovenhoek van de rechthoek die door het huidige object wordt weergegeven specificeert. |
| **float** [get_Right](./get_right/)() const | Retourneert de X-coördinaat van de rechterrand van de rechthoek die door het huidige object wordt weergegeven. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Retourneert een instantie van de [SizeF](../sizef/) klasse die de breedte en hoogte van de rechthoek die door het huidige object wordt weergegeven specificeert. |
| **float** [get_Top](./get_top/)() const | Retourneert de Y-coördinaat van de bovenrand van de rechthoek die door het huidige object wordt weergegeven. |
| **float** [get_Width](./get_width/)() const | Retourneert de breedte van de rechthoek die door het huidige object wordt weergegeven. |
| **float** [get_X](./get_x/)() const | Retourneert de X-coördinaat van de linkerbovenhoek van de rechthoek die door het huidige object wordt weergegeven. |
| **float** [get_Y](./get_y/)() const | Retourneert de Y-coördinaat van de linkerbovenhoek van de rechthoek die door het huidige object wordt weergegeven. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode van het huidige object. |
| void [Inflate](./inflate/)(**float**, **float**) | Vergroot de breedte en hoogte van de rechthoek die door het huidige object wordt weergegeven, waarbij de locatie van het geometrisch middelpunt van de rechthoek behouden blijft. De breedte en hoogte worden in beide richtingen met de opgegeven hoeveelheden vergroot. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Vergroot de breedte en hoogte van de rechthoek die door het huidige object wordt weergegeven, terwijl de locatie van het geometrisch middelpunt behouden blijft. De breedte en hoogte worden in beide richtingen vergroot met de hoeveelheden die respectievelijk door de breedte- en hoogtewaarden van het opgegeven grootte-object worden opgegeven. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Vergroot de breedte en hoogte van de rechthoek die door het opgegeven object wordt weergegeven, waarbij de locatie van het geometrisch middelpunt behouden blijft. De breedte en hoogte worden in beide richtingen met de opgegeven hoeveelheden vergroot. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Vervangt de rechthoek die door het huidige object wordt weergegeven door de rechthoek die het resultaat is van de intersectie met de rechthoek die door het opgegeven object wordt weergegeven. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Retourneert een rechthoek die het resultaat is van de intersectie van de opgegeven rechthoeken. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Bepaalt of de rechthoeken die door het huidige en opgegeven object worden weergegeven elkaar snijden. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Verschuift de positie van de rechthoek die door het huidige object wordt weergegeven met de opgegeven hoeveelheden. |
| void [Offset](./offset/)(**float**, **float**) | Verschuift de positie van de rechthoek die door het huidige object wordt weergegeven met de opgegeven hoeveelheden. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Retourneert altijd true. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Retourneert altijd false. |
| [RectangleF](./rectanglef/)() | Construeert een nieuw exemplaar van [RectangleF](./) object dat een rechthoek representeert met X- en Y-coördinaten en breedte- en hoogte-waarden ingesteld op 0. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Construeert een nieuw exemplaar van [RectangleF](./) object dat een rechthoek representeert met de opgegeven coördinaten van de linkerbovenhoek en breedte en hoogte. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Construeert een nieuw exemplaar van [RectangleF](./) object dat een rechthoek representeert waarvan de coördinaten van de linkerbovenhoek zijn opgegeven als een instantie van de [PointF](../pointf/) klasse en de breedte en hoogte als een instantie van de [SizeF](../sizef/) klasse. |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Construeert een nieuw exemplaar van [RectangleF](./) object dat de rechthoek die gelijk is aan de opgegeven representeert. |
| void [set_Height](./set_height/)(**float**) | Stelt de hoogte van de rechthoek die door het huidige object wordt weergegeven in. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Stelt de locatie van de linkerbovenhoek van de rechthoek die door het huidige object wordt weergegeven in. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Stelt de breedte en hoogte van de rechthoek die door het huidige object wordt weergegeven in. |
| void [set_Width](./set_width/)(**float**) | Stelt de breedte van de rechthoek die door het huidige object wordt weergegeven in. |
| void [set_X](./set_x/)(**float**) | Stelt de X-coördinaat van de linkerbovenhoek van de rechthoek die door het huidige object wordt weergegeven in. |
| void [set_Y](./set_y/)(**float**) | Stelt de Y-coördinaat van de linkerbovenhoek van de rechthoek die door het huidige object wordt weergegeven in. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Retourneert de stringrepresentatie van het huidige object. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Retourneert een rechthoek die het resultaat is van de unie van de opgegeven rechthoeken. |

## Velden

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Een lege rechthoek, d.w.z. een rechthoek waarvan de locatie- en grootte-waarden nul zijn. |

## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)