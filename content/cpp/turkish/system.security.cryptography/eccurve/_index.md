---
title: ECCurve
second_title: Aspose.Slides için C++ API Referansı
description: Eliptik bir eğri.
type: docs
weight: 716
url: /tr/system.security.cryptography/eccurve/
---
## ECCurve yapısı

Eliptik bir eğri.

```cpp
class ECCurve
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Belirtilen OID dostane adıyla bir eğri oluşturur. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Belirtilen oid'den bir eğri oluşturur. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Belirtilen OID değerinden bir eğri oluşturur. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | [Oid](../oid/)'i temsil eden isimlendirilmiş eğriyi alır. |
| void [Validate](./validate/)() const | Mevcut eğriyi doğrula. |

## Enum

| Enum | Açıklama |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Eliptik eğrinin tipi. |

## Diğer

* Ad Alanı [System::Security::Cryptography](../)
* Kütüphane [Aspose.Slides](../../)