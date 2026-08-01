---
title: Size
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een paar gehele getallen voor die de breedte en hoogte van een afbeelding weergeven. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 274
url: /nl/system.drawing/size/
---
## Grootteklasse

Stelt een paar gehele getallen voor die de breedte en hoogte van een afbeelding weergeven. Dit type moet op de stapel worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Size
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Retourneert een nieuw [Size](./) object dat de som is van het opgegeven [Size](./) object, d.w.z. waarvan de breedtewaarde gelijk is aan de som van de breedtewaarden van de opgegeven objecten en de hoogtewaarde gelijk is aan de som van de hoogtewaarden van de opgegeven objecten. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Construeert een [Size](./) object van het opgegeven [SizeF](../sizef/) object door de breedte- en hoogtewaarden van het [SizeF](../sizef/) object af te ronden naar de eerstvolgende hogere gehele waarden. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Bepaalt of het huidige object en het opgegeven object gelijk zijn, d.w.z. hetzelfde paar breedte- en hoogtewaarden vertegenwoordigen. |
| int [get_Height](./get_height/)() const | Retourneert de waarde van de hoogte die wordt vertegenwoordigd door het huidige object. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bepaalt of zowel breedte- als hoogtewaarden gelijk zijn aan 0. |
| int [get_Width](./get_width/)() const | Retourneert de waarde van de breedte die wordt vertegenwoordigd door het huidige object. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
|  [operator Point](./operator_point/)() const | Construeert een instantie van [Point](../point/) object en initialiseert de X- en Y-coördinaat met respectievelijk de breedte- en hoogtewaarden van het huidige object. |
|  [operator SizeF](./operator_sizef/)() const | Construeert een instantie van [SizeF](../sizef/) object en initialiseert deze met de breedte- en hoogtewaarden van het huidige [Size](./) object. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Construeert een [Size](./) object van het opgegeven [SizeF](../sizef/) object door de breedte- en hoogtewaarden van het [SizeF](../sizef/) object af te ronden naar de dichtstbijzijnde gehele waarden. |
| void [set_Height](./set_height/)(int) | Stelt de waarde van de hoogte in die wordt vertegenwoordigd door het huidige object. |
| void [set_Width](./set_width/)(int) | Stelt de waarde van de breedte in die wordt vertegenwoordigd door het huidige object. |
|  [Size](./size/)() | Construeert een nieuw [Size](./) object en initialiseert de breedte- en hoogtewaarden met 0. |
|  [Size](./size/)(const [Point](../point/)\&) | Construeert een nieuw [Size](./) object en initialiseert de breedte- en hoogtewaarden met respectievelijk de waarden van de X- en Y-coördinaten van het gespecificeerde punt. |
|  [Size](./size/)(int, int) | Construeert een nieuw [Size](./) object en initialiseert het met de opgegeven waarde. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Retourneert een nieuw [Size](./) object dat het resultaat is van de aftrekking van **size2** van **size1**, d.w.z. waarvan de breedtewaarde het resultaat is van de aftrekking van de breedtewaarde van **size2** van de breedtewaarde van **size1** en de hoogtewaarde het resultaat is van de aftrekking van de hoogtewaarde van **size2** van de hoogtewaarde van **size1**. |
| [String](../../system/string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van het paar breedte- en hoogtewaarden dat wordt vertegenwoordigd door het huidige object. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Construeert een [Size](./) object van het opgegeven [SizeF](../sizef/) object door de breedte- en hoogtewaarden van het [SizeF](../sizef/) object af te kappen op de eerstvolgende lagere gehele waarden. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Empty](./empty/) | Een lege instantie van [Size](./) klasse waarvan de breedte- en hoogtewaarden 0 zijn. |

## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)