---
title: GetNameInfo()
second_title: Aspose.Slides dla dokumentacji API C++
description: Pobiera nazwę podmiotu lub wystawcy z certyfikatu.
type: docs
weight: 248
url: /pl/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method

Pobiera nazwę podmiotu lub wystawcy z certyfikatu.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Opcje formatowania nazwy. |
| for_issuer | **bool** | Jeśli true, zwraca nazwę wystawcy, w przeciwnym razie zwraca nazwę podmiotu. |

### Wartość zwracana

Sformatowana nazwa wystawcy lub podmiotu.

## Zobacz także

* Enum [X509NameType](../../x509nametype/)
* Class [String](../../../system/string/)
* Class [X509Certificate2](../)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)