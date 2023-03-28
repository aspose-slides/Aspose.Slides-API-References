---
title: ECCurve
second_title: Aspose.Slides for C++ API Reference
description: An elliptic curve.
type: docs
weight: 716
url: /cpp/system.security.cryptography/eccurve/
---
## ECCurve struct


An elliptic curve.

```cpp
class ECCurve
```

## Methods

| Method | Description |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Create a curve from the specified OID firendly name. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Create a curve from the specified oid. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Create a curve from the specified OID value. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Gets [Oid](../oid/) representing the named curve. |
| void [Validate](./validate/)() const | Validate the current curve. |
## Enums

| Enum | Description |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Type of elliptic curve. |
## See Also

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)
