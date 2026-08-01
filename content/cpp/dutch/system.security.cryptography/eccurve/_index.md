---
title: ECCurve
second_title: Aspose.Slides voor C++ API-referentie
description: Een elliptische curve.
type: docs
weight: 716
url: /nl/system.security.cryptography/eccurve/
---
## ECCurve struct

Een elliptische curve.

```cpp
class ECCurve
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Maak een curve op basis van de opgegeven OID-vriendelijke naam. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Maak een curve op basis van de opgegeven oid. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Maak een curve op basis van de opgegeven OID-waarde. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Haalt [Oid](../oid/) op die de benoemde curve vertegenwoordigt. |
| void [Validate](./validate/)() const | Valideer de huidige curve. |

## Enumeraties

| Enum | Beschrijving |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Type van elliptische curve. |

## Zie ook

* Naamruimte [System::Security::Cryptography](../)
* Bibliotheek [Aspose.Slides](../../)