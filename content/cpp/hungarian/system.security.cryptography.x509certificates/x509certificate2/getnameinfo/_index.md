---
title: GetNameInfo()
second_title: Aspose.Slides for C++ API referencia
description: Lekéri a tanúsítvány alany vagy kibocsátó nevét.
type: docs
weight: 248
url: /hu/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const metódus

A tanúsítványból lekéri a tárgy vagy a kibocsátó nevét.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Névformázási beállítások. |
| for_issuer | **bool** | Ha igaz, visszaadja a kibocsátó nevét, egyébként a tárgy nevét. |

### Visszatérési érték

Formázott kibocsátó vagy tárgy neve.

## Lásd még

* Enum [X509NameType](../../x509nametype/)
* Osztály [String](../../../system/string/)
* Osztály [X509Certificate2](../)
* Névtér [System::Security::Cryptography::X509Certificates](../../)
* Könyvtár [Aspose.Slides](../../../)