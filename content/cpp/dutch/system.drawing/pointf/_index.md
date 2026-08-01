---
title: PointF
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een paar enkelprecisie zwevend-kommagetal X- en Y-coördinaten van een punt op een tweedimensionaal vlak voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 222
url: /nl/system.drawing/pointf/
---
## PointF klasse

Stelt een paar enkelprecisie zwevende-kommagetal X- en Y-coördinaten van een punt op een 2-dimensionaal vlak voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
class PointF
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Voegt de breedte- en hoogtewaarden van het opgegeven [SizeF](../sizef/) object toe aan de X- en Y-coördinaatwaarden van het opgegeven [PointF](./) object overeenkomstig. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Voegt de breedte- en hoogtewaarden van het opgegeven [Size](../size/) object toe aan de X- en Y-coördinaatwaarden van het opgegeven [PointF](./) object overeenkomstig. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Bepaalt of het huidige object en het opgegeven object gelijk zijn, dwz dezelfde paar X- en Y-coördinaatwaarden vertegenwoordigen. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bepaalt of zowel X- als Y-coördinaatwaarden gelijk zijn aan 0. |
| **float** [get_X](./get_x/)() const | Retourneert de waarde van de X-coördinaat die door het huidige object wordt vertegenwoordigd. |
| **float** [get_Y](./get_y/)() const | Retourneert de waarde van de Y-coördinaat die door het huidige object wordt vertegenwoordigd. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| **bool** [IsNull](./isnull/)() const | Retourneert altijd false. |
| explicit  [operator bool](./operator_bool/)() | Retourneert altijd true. |
|  [PointF](./pointf/)() | Construeert een nieuw [PointF](./) object en initialiseert zijn X- en Y-coördinaatwaarden met 0. |
|  [PointF](./pointf/)(**float**, **float**) | Construeert een nieuw [PointF](./) object en initialiseert het met de opgegeven waarden. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Construeert een nieuw [PointF](./) object en initialiseert zijn X- en Y-coördinaatwaarden met de breedte- en hoogtewaarden van het opgegeven [SizeF](../sizef/) object overeenkomstig. |
| void [set_X](./set_x/)(**float**) | Stelt de waarde van de X-coördinaat in die door het huidige object wordt vertegenwoordigd. |
| void [set_Y](./set_y/)(**float**) | Stelt de waarde van de Y-coördinaat in die door het huidige object wordt vertegenwoordigd. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Trekt de breedte- en hoogtewaarden van het opgegeven [SizeF](../sizef/) object af van de X- en Y-coördinaatwaarden van het opgegeven [PointF](./) object overeenkomstig. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Trekt de breedte- en hoogtewaarden van het opgegeven [Size](../size/) object af van de X- en Y-coördinaatwaarden van het opgegeven [PointF](./) object overeenkomstig. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van het paar X- en Y-coördinaatwaarden dat door het huidige object wordt vertegenwoordigd. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Empty](./empty/) | Een lege instantie van [PointF](./) klasse waarvan de X- en Y-coördinaatwaarden 0 zijn. |

## Zie ook

* Namespace [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)