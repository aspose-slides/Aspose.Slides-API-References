---
title: ECCurve
second_title: Referencja API Aspose.Slides dla C++
description: Krzywa eliptyczna.
type: docs
weight: 716
url: /pl/system.security.cryptography/eccurve/
---
## ECCurve struct

Krzywa eliptyczna.

```cpp
class ECCurve
```

## Metody

| Metoda | Opis |
| --- | --- |
| static [ECCurve](./) [CreateFromFriendlyName](./createfromfriendlyname/)(const [String](../../system/string/)\&) | Utwórz krzywą z określonej przyjaznej nazwy OID. |
| static [ECCurve](./) [CreateFromOid](./createfromoid/)(const [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\>\&) | Utwórz krzywą z określonego oid. |
| static [ECCurve](./) [CreateFromValue](./createfromvalue/)(const [String](../../system/string/)\&) | Utwórz krzywą z określonej wartości OID. |
| **bool** [get_IsCharacteristic2](./get_ischaracteristic2/)() const |  |
| **bool** [get_IsExplicit](./get_isexplicit/)() const |  |
| **bool** [get_IsNamed](./get_isnamed/)() const |  |
| **bool** [get_IsPrime](./get_isprime/)() const |  |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../oid/)\> [get_Oid](./get_oid/)() const | Zwraca [Oid](../oid/) reprezentujący nazwaną krzywą. |
| void [Validate](./validate/)() const | Sprawdź poprawność bieżącej krzywej. |
## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [ECCurveType](./eccurvetype/) | Typ krzywej eliptycznej. |
## Zobacz także

* Namespace [System::Security::Cryptography](../)
* Library [Aspose.Slides](../../)