---
title: BitVector32
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller en enkel lätt bitvektor med enkel heltals- eller boolesk åtkomst till ett 32-bitars lagringsutrymme.
type: docs
weight: 1
url: /sv/system.collections.specialized/bitvector32/
---
## BitVector32 klass

Tillhandahåller en enkel lätt bitvektor med enkel heltals- eller [Boolean](../../system/boolean/) åtkomst till ett 32-bitars lagringsutrymme.

```cpp
class BitVector32
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Initierar en ny tom instans av [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Initierar en ny instans av strukturen [BitVector32](./) med den angivna interna data. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Initierar en ny instans av strukturen [BitVector32](./) med informationen i det angivna värdet. |
| static **int32_t** [CreateMask](./createmask/)() | Skapar den första masken i en serie. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Skapar nästa mask i en serie. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Skapar den första sektionen i en serie, med det angivna maximala värdet. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Skapar nästa sektion i en serie, med det angivna maximala värdet. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Bestämmer om det angivna objektet är det samma som det aktuella. |
| **int32_t** [get_Data](./get_data/)() | returnerar den rådata som lagras i denna bitvektor... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Returnerar en hashkod för det aktuella objektet. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Hämtar ett värde som indikerar om alla angivna bitar är satta. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Hämtar värdet för den angivna sektionen. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Sätter ett värde som indikerar om alla angivna bitar är satta. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Sätter värdet för den angivna sektionen. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Konverterar värdet som representeras av värdeparametern till sträng. |
| [String](../../system/string/) [ToString](./tostring/)() const | Konverterar värdet som representeras av det aktuella objektet till sträng. |

## Se även

* Namnrymd [System::Collections::Specialized](../)
* Bibliotek [Aspose.Slides](../../)