---
title: GetNameInfo()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt onderwerps- of uitgeversnaam op uit het certificaat.
type: docs
weight: 248
url: /nl/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method


Haalt de onderwerps- of uitgeversnaam op uit het certificaat.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Opties voor naamopmaak. |
| for_issuer | **bool** | Als true, retourneert de uitgeversnaam, anders de onderwerpsnaam. |

### Retourwaarde

Geformatteerde uitgevers- of onderwerpsnaam.

## Zie ook

* Enum [X509NameType](../../x509nametype/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)