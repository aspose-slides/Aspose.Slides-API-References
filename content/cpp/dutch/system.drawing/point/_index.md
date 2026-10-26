---
title: Point
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een paar gehele X- en Y-coördinaten van een punt op een tweedimensionaal vlak voor. Dit type moet op de stack worden gealloceerd en aan functies per waarde of per referentie worden doorgegeven. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 209
url: /nl/system.drawing/point/
---
## Point klasse


Stelt een paar gehele X- en Y-coördinaten van een punt op een 2-dimensionaal vlak voor. Dit type moet op de stack worden gealloceerd en aan functies doorgegeven worden per waarde of per verwijzing. Gebruik nooit de [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Point
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | Voegt de breedte- en hoogtewaarden van het opgegeven [Size](../size/) object toe aan de X- en Y-coördinaatwaarden van het opgegeven [Point](./) object overeenkomstig. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Construeert een [Point](./) object van het opgegeven [PointF](../pointf/) object door de X- en Y-coördinaatwaarden van het [PointF](../pointf/) object af te ronden naar de volgende hogere gehele getallen. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Bepaalt of het huidige object en het opgegeven object gelijk zijn, d.w.z. dezelfde paar X- en Y-coördinaatwaarden vertegenwoordigen. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bepaalt of zowel X- als Y-coördinaatwaarden gelijk zijn aan 0. |
| int [get_X](./get_x/)() const | Retourneert de waarde van de X-coördinaat die door het huidige object wordt vertegenwoordigd. |
| int [get_Y](./get_y/)() const | Retourneert de waarde van de Y-coördinaat die door het huidige object wordt vertegenwoordigd. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| size_t [getStdHash](./getstdhash/)() const | Retourneert een hashwaarde voor het huidige object. |
| **bool** [IsNull](./isnull/)() const | Retourneert altijd false. |
| void [Offset](./offset/)(int, int) | Verschuift de X- en Y-coördinaatwaarde die door het huidige object wordt vertegenwoordigd met de opgegeven waarden. |
| void [Offset](./offset/)([Point](./)) | Verschuift de X- en Y-coördinaten die door het huidige object worden vertegenwoordigd met de waarden van X- en Y-coördinaten van het opgegeven [Point](./) object overeenkomstig. |
| [operator PointF](./operator_pointf/)() const | Construeert een exemplaar van het [PointF](../pointf/) object en initialiseert het met de X- en Y-coördinaatwaarden van het huidige [Point](./) object. |
| [operator Size](./operator_size/)() const | Construeert een exemplaar van het [Size](../size/) object en initialiseert de breedte- en hoogtewaarden met de X- en Y-coördinaatwaarden die door het huidige object worden vertegenwoordigd overeenkomstig. |
| [Point](./point/)() | Construeert een nieuw [Point](./) object en initialiseert de X- en Y-coördinaatwaarden met 0. |
| [Point](./point/)(int, int) | Construeert een nieuw [Point](./) object en initialiseert het met de opgegeven waarden. |
| [Point](./point/)(const [Size](../size/)\&) | Construeert een nieuw [Point](./) object en initialiseert de X- en Y-coördinaatwaarden met de breedte- en hoogtewaarden van het opgegeven [SizeF](../sizef/) object overeenkomstig. |
| [Point](./point/)(int) | Construeert een nieuw [Point](./) object en initialiseert de X-coördinaatwaarde met een waarde gevormd door de hoge 16 bits van de opgegeven 32-bit integer en de Y-coördinaatwaarde met een waarde gevormd door de lage 16 bits van de opgegeven 32-bit integerwaarde. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Construeert een [Point](./) object van het opgegeven [PointF](../pointf/) object door de X- en Y-coördinaatwaarden van het [PointF](../pointf/) object af te ronden op de dichtstbijzijnde gehele getallen. |
| void [set_X](./set_x/)(int) | Stelt de waarde van de X-coördinaat in die door het huidige object wordt vertegenwoordigd. |
| void [set_Y](./set_y/)(int) | Stelt de waarde van de Y-coördinaat in die door het huidige object wordt weergegeven. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | Trekt de breedte- en hoogtewaarden van het opgegeven [Size](../size/) object af van de X- en Y-coördinaatwaarden van het opgegeven [Point](./) object overeenkomstig. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van het paar X- en Y-coördinaatwaarden dat door het huidige object wordt vertegenwoordigd. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Construeert een [Point](./) object van het opgegeven [PointF](../pointf/) object door de X- en Y-coördinaatwaarden van het [PointF](../pointf/) object af te kappen op de volgende lagere gehele getallen. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Empty](./empty/) | Een lege instantie van de [Point](./) klasse waarvan de X- en Y-coördinaatwaarden 0 zijn. |

## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)