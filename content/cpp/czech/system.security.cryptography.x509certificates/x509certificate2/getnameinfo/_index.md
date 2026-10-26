---
title: GetNameInfo()
second_title: Aspose.Slides pro C++ – reference API
description: Získá název subjektu nebo vydavatele z certifikátu.
type: docs
weight: 248
url: /cs/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const metoda


Získá název subjektu nebo vydavatele z certifikátu.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Možnosti formátování názvu. |
| for_issuer | **bool** | Pokud je true, vrátí název vydavatele, jinak vrátí název subjektu. |

### Návratová hodnota

Formátovaný název vydavatele nebo subjektu.

## Viz také

* Enum [X509NameType](../../x509nametype/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)