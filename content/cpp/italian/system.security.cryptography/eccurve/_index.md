---
title: ECCurve
second_title: Riferimento API di Aspose.Slides per C++
description: Una curva ellittica.
type: docs
weight: 716
url: /it/system.security.cryptography/eccurve/
---
## ECCurve struct

Una curva ellittica.

```cpp
class ECCurve
```

## Methods

| Method | Description |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Crea una curva dal nome amichevole OID specificato. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Crea una curva dall'oid specificato. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Crea una curva dal valore OID specificato. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Ottiene [Oid](../oid/) che rappresenta la curva denominata. |
| void [Validate](./validate/)() const | Convalida la curva corrente. |

## Enums

| Enum | Description |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Tipo di curva ellittica. |

## Vedi anche

* Spazio dei nomi [System::Security::Cryptography](../)
* Libreria [Aspose.Slides](../../)