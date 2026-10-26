---
title: Index
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een index in een collectie voor. De index kan van het begin of van het einde komen. Dit type moet op de stack worden gealloceerd en aan functies per waarde of per referentie worden doorgegeven. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 1015
url: /nl/system/index/
---
## Index klasse

Stelt een index in een collectie voor. De index kan van het begin of van het einde komen. Dit type moet op de stack worden gealloceerd en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Bepaalt of de huidige instantie en de gespecificeerde [Index](./) dezelfde positie vertegenwoordigen. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Maakt een [Index](./) die relatief is ten opzichte van het einde van de collectie. |
| static constexpr [Index](./) [get_End](./get_end/)() | Haalt een [Index](./) object dat het einde van een collectie vertegenwoordigt. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Haalt een waarde op die aangeeft of de index van het einde komt. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Haalt een [Index](./) object dat het begin van een collectie vertegenwoordigt. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Haalt de indexwaarde op. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor de huidige index. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Converteert de huidige [Index](./) naar een offset vanaf het begin van een collectie met de gespecificeerde lengte. |
| constexpr [Index](./index/)() | Construeert een instantie die het begin van een collectie vertegenwoordigt. |
| constexpr [Index](./index/)(**int32_t**) | Construeert een instantie die de gespecificeerde positie vanaf het begin van een collectie vertegenwoordigt. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Construeert een instantie die de gespecificeerde index vertegenwoordigt. |
## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)