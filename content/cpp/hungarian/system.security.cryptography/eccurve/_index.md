---
title: ECCurve
second_title: Aspose.Slides C++ API Referencia
description: Egy elliptikus görbe.
type: docs
weight: 716
url: /hu/system.security.cryptography/eccurve/
---
## ECCurve struktúra

Egy elliptikus görbe.

```cpp
class ECCurve
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Létrehozza a görbét a megadott OID barátságos név alapján. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Létrehozza a görbét a megadott oid alapján. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Létrehozza a görbét a megadott OID érték alapján. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Megkapja a [Oid](../oid/)-t, amely a névvel ellátott görbét képviseli. |
| void [Validate](./validate/)() const | Érvényesíti az aktuális görbét. |

## Enumok

| Enum | Leírás |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Az elliptikus görbe típusa. |

## Lásd még

* Névterület [System::Security::Cryptography](../)
* Könyvtár [Aspose.Slides](../../)