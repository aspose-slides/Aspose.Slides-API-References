---
title: GetNameInfo()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντλεί το όνομα του υποκειμένου ή του εκδότη από το πιστοποιητικό.
type: docs
weight: 248
url: /el/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const μέθοδος

Αντλεί το όνομα του υποκειμένου ή του εκδότη από το πιστοποιητικό.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | Επιλογές μορφοποίησης ονόματος. |
| for_issuer | **bool** | Εάν είναι true, επιστρέφει το όνομα του εκδότη, αλλιώς επιστρέφει το όνομα του υποκειμένου. |

### Τιμή Επιστροφής

Μορφοποιημένο όνομα εκδότη ή υποκειμένου.

## Δείτε επίσης

* Enum [X509NameType](../../x509nametype/)
* Κλάση [String](../../../system/string/)
* Κλάση [X509Certificate2](../)
* Ονομαχώρος [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)