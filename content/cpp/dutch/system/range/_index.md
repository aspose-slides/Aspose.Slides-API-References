---
title: Range
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een bereik voor met een start- en eindindex. Dit type moet op de stack worden gealloceerd en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 1197
url: /nl/system/range/
---
## Range klasse

Stelt een bereik voor met een start- en eindindex. Dit type moet op de stack worden gealloceerd en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Creëert een bereik dat begint bij het begin van de collectie en eindigt op de opgegeven eindindex. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Bepaalt of het huidige bereik gelijk is aan het opgegeven bereik. |
| static constexpr [Range](./) [get_All](./get_all/)() | Retourneert een [Range](./) die de volledige collectie weergeeft. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Haalt de eindindex op. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Haalt de startindex op. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige bereik. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Berekent de nulgebaseerde startverschuiving en lengte voor de opgegeven collectielengte. |
| constexpr [Range](./range/)() | Construeert een leeg bereik. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Construeert een [Range](./) uit de opgegeven start- en eindindexen. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Creëert een bereik dat begint bij de opgegeven startindex en zich uitstrekt tot het einde van de collectie. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)