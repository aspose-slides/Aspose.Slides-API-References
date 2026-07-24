---
title: GetNameInfo()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest den Betreff- oder Ausstellernamen aus dem Zertifikat.
type: docs
weight: 248
url: /de/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const Methode

Liest den Betreff- oder Ausstellernamen aus dem Zertifikat.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Optionen zur Namensformatierung. |
| for_issuer | **bool** | Falls true, gibt den Ausstellernamen zurück, andernfalls den Betreffnamen. |

### Rückgabewert

Formatierter Aussteller- oder Betreffname.

## Siehe auch

* Enum [X509NameType](../../x509nametype/)
* Klasse [String](../../../system/string/)
* Klasse [X509Certificate2](../)
* Namensraum [System::Security::Cryptography::X509Certificates](../../)
* Bibliothek [Aspose.Slides](../../../)