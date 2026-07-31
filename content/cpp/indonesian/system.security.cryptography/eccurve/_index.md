---
title: ECCurve
second_title: Referensi API Aspose.Slides untuk C++
description: Sebuah kurva eliptik.
type: docs
weight: 716
url: /id/system.security.cryptography/eccurve/
---
## ECCurve struct

Sebuah kurva eliptik.

```cpp
class ECCurve
```

## Metode

| Method | Deskripsi |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Buat kurva dari nama ramah OID yang ditentukan. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Buat kurva dari oid yang ditentukan. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Buat kurva dari nilai OID yang ditentukan. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Mendapatkan [Oid](../oid/) yang mewakili kurva bernama. |
| void [Validate](./validate/)() const | Validasi kurva saat ini. |

## Enum

| Enum | Deskripsi |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Jenis kurva eliptik. |

## Lihat Juga

* Namespace [System::Security::Cryptography](../)
* Perpustakaan [Aspose.Slides](../../)