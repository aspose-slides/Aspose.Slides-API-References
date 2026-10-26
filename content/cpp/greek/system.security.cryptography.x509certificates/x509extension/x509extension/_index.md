---
title: X509Extension()
second_title: Aspose.Slides για C++ API Αναφορά
description: Κατασκευαστής.
type: docs
weight: 1
url: /el/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | Κωδικοποιημένα δεδομένα που σχετίζονται με το πιστοποιητικό. |
| critical | **bool** | Σήμα κρισιμότητας. |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) αναγνωριστικό που σχετίζεται με την επέκταση. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακατέργαστα δεδομένα που σχετίζονται με το πιστοποιητικό. |
| critical | **bool** | Σήμα κρισιμότητας. |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) constructor

Constructor.

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) αναγνωριστικό που σχετίζεται με την επέκταση. |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Ακατέργαστα δεδομένα που σχετίζονται με το πιστοποιητικό. |
| critical | **bool** | Σήμα κρισιμότητας. |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Κλάση [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Κλάση [X509Extension](../)
* Κλάση [Oid](../../../system.security.cryptography/oid/)
* Κλάση [String](../../../system/string/)
* Χώρος ονομάτων [System::Security::Cryptography::X509Certificates](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)