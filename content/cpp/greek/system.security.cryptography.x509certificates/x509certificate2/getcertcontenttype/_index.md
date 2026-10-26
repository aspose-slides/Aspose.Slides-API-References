---
title: GetCertContentType()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει τον τύπο του πιστοποιητικού που περιέχεται στον καθορισμένο πίνακα byte.
type: docs
weight: 391
url: /el/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) μέθοδος

Επιστρέφει τον τύπο του πιστοποιητικού που περιέχεται στον καθορισμένο πίνακα byte.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα πιστοποιητικού. |

### Τιμή επιστροφής

Τύπος πιστοποιητικού X.509.

## X509Certificate2::GetCertContentType(const String\&) μέθοδος

Επιστρέφει τον τύπο του πιστοποιητικού που περιέχεται στο καθορισμένο αρχείο.

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Όνομα αρχείου πιστοποιητικού. |

### Τιμή επιστροφής

Τύπος πιστοποιητικού X.509.

## Δείτε επίσης

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Κλάση [X509Certificate2](../)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)