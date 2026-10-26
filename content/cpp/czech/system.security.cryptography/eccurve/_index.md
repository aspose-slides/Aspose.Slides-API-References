---
title: ECCurve
second_title: Aspose.Slides – referenční příručka API pro C++
description: Eliptická křivka.
type: docs
weight: 716
url: /cs/system.security.cryptography/eccurve/
---
## ECCurve struktura

Eliptická křivka.

```cpp
class ECCurve
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Vytvoří křivku ze zadaného přátelského názvu OID. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Vytvoří křivku ze zadaného oid. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Vytvoří křivku ze zadané hodnoty OID. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Získá [Oid](../oid/) představující pojmenovanou křivku. |
| void [Validate](./validate/)() const | Ověří aktuální křivku. |

## Výčty

| Výčet | Popis |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Typ eliptické křivky. |

## Viz také

* Jmenný prostor [System::Security::Cryptography](../)
* Knihovna [Aspose.Slides](../../)