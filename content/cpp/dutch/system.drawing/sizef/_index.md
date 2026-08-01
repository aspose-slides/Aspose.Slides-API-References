---
title: SizeF
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een paar enkele-precisie zwevend-kommagetallen voor die de breedte en hoogte van een afbeelding weergeven. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 287
url: /nl/system.drawing/sizef/
---
## SizeF klasse


Stelt een paar enkele-precisie zwevend-kommagetallen voor die de breedte en hoogte van een afbeelding weergeven. Dit type moet op de stack worden gealloceerd en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
class SizeF
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Retourneert een nieuw [SizeF](./) object dat de som is van de opgegeven [SizeF](./) objecten, d.w.z. waarvan de breedtewaarde gelijk is aan de som van de breedtewaarden van de opgegeven objecten en de hoogtewaarde gelijk is aan de som van de hoogtewaarden van de opgegeven objecten. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Bepaalt of het huidige object en het opgegeven object gelijk zijn, d.w.z. dezelfde paar breedte- en hoogtewaarden vertegenwoordigen. |
| **float** [get_Height](./get_height/)() const | Retourneert de waarde van de hoogte die wordt vertegenwoordigd door het huidige object. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Bepaalt of zowel de breedte- als de hoogtewaarden gelijk zijn aan 0. |
| **float** [get_Width](./get_width/)() const | Retourneert de waarde van de breedte die wordt vertegenwoordigd door het huidige object. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
|  [operator PointF](./operator_pointf/)() const | Zet het huidige object om naar een instantie van [Point](../point/) object door zijn X- en Y-coördinaat te initialiseren met respectievelijk de breedte- en hoogtewaarden van het huidige object. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Voegt de breedte- en hoogtewaarden van het opgegeven [SizeF](./) object toe aan de breedte- en hoogtewaarden van het huidige [SizeF](./) object respectievelijk. |
| void [set_Height](./set_height/)(**float**) | Stelt de waarde van de hoogte in die wordt vertegenwoordigd door het huidige object. |
| void [set_Width](./set_width/)(**float**) | Stelt de waarde van de breedte in die wordt vertegenwoordigd door het huidige object. |
|  [SizeF](./sizef/)() | Construeert een nieuw [SizeF](./) object en initialiseert zijn breedte- en hoogtewaarden met 0. |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Construeert een nieuw [SizeF](./) object en initialiseert zijn breedte- en hoogtewaarden met respectievelijk de waarden van de X- en Y-coördinaten van het opgegeven punt. |
|  [SizeF](./sizef/)(**float**, **float**) | Construeert een nieuw [SizeF](./) object en initialiseert het met de opgegeven waarden. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Retourneert een nieuw [SizeF](./) object dat het resultaat is van de aftrekking van **size2** van **size1**, d.w.z. waarvan de breedtewaarde het resultaat is van de aftrekking van de breedtewaarde van **size2** van de breedtewaarde van **size1**, en de hoogtewaarde het resultaat is van de aftrekking van de hoogtewaarde van **size2** van de hoogtewaarde van **size1**. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Zet het huidige object om naar een instantie van [Point](../point/) object door zijn X- en Y-coördinaat te initialiseren met respectievelijk de breedte- en hoogtewaarden van het huidige object. |
| [Size](../size/) [ToSize](./tosize/)() const | Construeert een [Size](../size/) object uit het huidige [SizeF](./) object door de breedte- en hoogtewaarden van het [SizeF](./) object af te kappen tot de eerstvolgende lagere gehele waarden. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van het paar breedte- en hoogtewaarden dat door het huidige object wordt vertegenwoordigd. |
## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Empty](./empty/) | Een lege instantie van [SizeF](./) klasse waarvan de breedte- en hoogtewaarden 0 zijn. |
## Zie ook

* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)