---
title: BitVector32
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt een eenvoudige lichte bitvector met gemakkelijke integer- of booleaanse toegang tot een 32 bit opslag.
type: docs
weight: 1
url: /nl/system.collections.specialized/bitvector32/
---
## BitVector32 klasse


Biedt een eenvoudige lichte bitvector met gemakkelijke integer- of [Boolean](../../system/boolean/)-toegang tot een 32 bit opslag.

```cpp
class BitVector32
```

## Methoden

| Method | Description |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Initialiseert een nieuwe lege instantie van de [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Initialiseert een nieuwe instantie van de [BitVector32](./)-structuur met de opgegeven interne gegevens. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Initialiseert een nieuwe instantie van de [BitVector32](./)-structuur met de informatie in de opgegeven waarde. |
| static **int32_t** [CreateMask](./createmask/)() | Creëert de eerste maskering in een reeks. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Creëert de volgende maskering in een reeks. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Creëert de eerste sectie in een reeks, met de opgegeven maximale waarde. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Creëert de volgende sectie in een reeks, met de opgegeven maximale waarde. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Bepaalt of het opgegeven object hetzelfde is als het huidige. |
| **int32_t** [get_Data](./get_data/)() | Retourneert de ruwe gegevens die in deze bitvector zijn opgeslagen... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Retourneert een hashcode voor het huidige object. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Haalt een waarde op die aangeeft of alle opgegeven bits zijn ingesteld. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Haalt de waarde op voor de opgegeven sectie. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Stelt een waarde in die aangeeft of alle opgegeven bits zijn ingesteld. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Stelt de waarde in voor de opgegeven sectie. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Converteert de door de waardeparameter gerepresenteerde waarde naar een tekenreeks. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converteert de door het huidige object gerepresenteerde waarde naar een tekenreeks. |
## Zie ook

* Naamruimte [System::Collections::Specialized](../)
* Bibliotheek [Aspose.Slides](../../)