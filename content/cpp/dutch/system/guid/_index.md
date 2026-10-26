---
title: Guid
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een Globally Unique Identifier (GUID) voor. Dit type moet op de stack worden toegewezen en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 885
url: /nl/system/guid/
---
## Guid klasse

Stelt een Globally Unique Identifier (GUID) voor. Dit type moet op de stack worden toegewezen en doorgegeven aan functies per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
class Guid
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Voert een rekenkundige vergelijking uit van de GUID's die worden weergegeven door het huidige en het opgegeven object. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Bepaalt of de GUID's die worden weergegeven door het huidige en het opgegeven object gelijk zijn. |
| int [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| [Guid](./guid/)() | Construeert een object dat een GUID vertegenwoordigt die uit uitsluitend nullen bestaat. |
| [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Construeert een object dat een GUID vertegenwoordigt gespecificeerd als een array van onondertekende 8-bit gehele getallen. |
| [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Construeert een object dat een GUID vertegenwoordigt gespecificeerd als een array-view van onondertekende 8-bit gehele getallen. |
| [Guid](./guid/)(const [String](../string/)\&) | Construeert een object dat een GUID vertegenwoordigt gespecificeerd als een tekenreeks. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Construeert een instantie van de [Guid](./) klasse uit de opgegeven GUID-componenten. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Construeert een instantie van de [Guid](./) klasse uit de opgegeven GUID-componenten. |
| [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Construeert een instantie van de [Guid](./) klasse uit de opgegeven onondertekende gehele getallen en bytes. |
| [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Construeert een instantie van de [Guid](./) klasse uit de opgegeven onondertekende gehele getallen en bytes. |
| [Guid](./guid/)(const [Guid](./)\&) | Construeert een object dat dezelfde GUID vertegenwoordigt als het opgegeven object. |
| static [Guid](./) [NewGuid](./newguid/)() | Genereert een nieuwe GUID en retourneert een [Guid](./) object dat deze vertegenwoordigt. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Bepaalt of de GUID's die worden weergegeven door het huidige en het opgegeven object niet gelijk zijn. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Kenst aan het huidige object de GUID-waarde toe die wordt weergegeven door het opgegeven [Guid](./) object. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Bepaalt of de GUID's die worden weergegeven door het huidige en het opgegeven object gelijk zijn. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven tekenreeksrepresentatie van een GUID naar een gelijkwaardig [Guid](./) object. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Converteert de door het huidige object vertegenwoordigde GUID naar een array van bytes. |
| [String](../string/) [ToString](./tostring/)() const | Converteert de door het huidige object vertegenwoordigde GUID naar zijn tekenreeksrepresentatie. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converteert de door het huidige object vertegenwoordigde GUID naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converteert de door het huidige object vertegenwoordigde GUID naar zijn tekenreeksrepresentatie met behulp van het opgegeven tekenreeksformaat en Cultuur. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Probeert de opgegeven tekenreeks te converteren naar een [Guid](./) object. |
| [~Guid](./~guid/)() | Destruktor. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [Empty](./empty/) | Stelt een GUID voor die de waarde 0 heeft. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)