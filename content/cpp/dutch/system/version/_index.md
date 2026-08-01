---
title: Version
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een versienummer voor. Dit type moet op de stack worden gealloceerd en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 1470
url: /nl/system/version/
---
## Versieklasse

Stelt een versienummer voor. Dit type dient op de stack te worden gealloceerd en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Version
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Vergelijkt de versies die worden weergegeven door het huidige object en het opgegeven object. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Bepaalt of de versienummers die worden weergegeven door het huidige en het opgegeven object gelijk zijn. |
| int [get_Build](./get_build/)() const | Retourneert het build-nummer. |
| int [get_Major](./get_major/)() const | Retourneert de hoofdversie. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Retourneert de hoge 16-bit-waarde van het revisienummer. |
| int [get_Minor](./get_minor/)() const | Retourneert de onderversie. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Retourneert de lage 16-bit-waarde van het revisienummer. |
| int [get_Revision](./get_revision/)() const | Retourneert het revisienummer. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Converteert de tekenreeksrepresentatie van een versienummer naar een gelijkwaardig exemplaar van de [Version](./) klasse. |
| [String](../string/) [ToString](./tostring/)() const | Retourneert de tekenreeksrepresentatie van het versienummer dat wordt weergegeven door het huidige object. |
| [String](../string/) [ToString](./tostring/)(int) const | Retourneert de tekenreeksrepresentatie van het opgegeven aantal secties van het versienummer dat wordt weergegeven door het huidige object. |
|  [Version](./version/)(int, int, int, int) | Construeert een exemplaar dat de gespecificeerde hoofd-, onder-, build- en revisiewaarden vertegenwoordigt. |
|  [Version](./version/)(int, int, int) | Construeert een exemplaar dat de gespecificeerde hoofd-, onder- en buildwaarden vertegenwoordigt. |
|  [Version](./version/)(int, int) | Construeert een exemplaar dat de gespecificeerde hoofd- en waarden vertegenwoordigt. |
|  [Version](./version/)(const [String](../string/)\&) | Construeert een exemplaar dat het versienummer vertegenwoordigt dat als tekenreeks wordt weergegeven. |
|  [Version](./version/)() | Construeert een exemplaar dat het versienummer 0.0.-1.-1 vertegenwoordigt. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)