---
title: GetNameInfo()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar namn på ämne eller utfärdare från certifikatet.
type: docs
weight: 248
url: /sv/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const metod

Hämtar namn på ämne eller utfärdare från certifikatet.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Alternativ för namnformatering. |
| for_issuer | **bool** | Om true, returneras utfärdarens namn, annars returneras subjektets namn. |

### Returvärde

Formaterat utfärdar- eller subjekt-namn.

## Se också

* Enum [X509NameType](../../x509nametype/)
* Klass [String](../../../system/string/)
* Klass [X509Certificate2](../)
* Namnrymd [System::Security::Cryptography::X509Certificates](../../)
* Bibliotek [Aspose.Slides](../../../)