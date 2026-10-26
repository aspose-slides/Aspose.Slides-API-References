---
title: ECCurve
second_title: Aspose.Slides för C++ API-referens
description: En elliptisk kurva.
type: docs
weight: 716
url: /sv/system.security.cryptography/eccurve/
---
## ECCurve struct

En elliptisk kurva.

```cpp
class ECCurve
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Skapa en kurva från det angivna OID-vänliga namnet. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Skapa en kurva från det angivna OID-värdet. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Skapa en kurva från det angivna OID-värdet. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Hämtar [Oid](../oid/) som representerar den namngivna kurvan. |
| void [Validate](./validate/)() const | Validera den aktuella kurvan. |

## Enum

| Enum | Beskrivning |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Typ av elliptisk kurva. |

## Se även

* Namnrymd [System::Security::Cryptography](../)
* Bibliotek [Aspose.Slides](../../)