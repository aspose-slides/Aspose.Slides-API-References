---
title: VerifyHash()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει την υπογραφή των δεδομένων.
type: docs
weight: 222
url: /el/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Ελέγχει την υπογραφή των δεδομένων.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Κατακερματισμός που υπολογίζεται για τα ληφθέντα δεδομένα. |
| str | const [String](../../../system/string/)\& | Όνομα του αλγορίθμου κατακερματισμού που χρησιμοποιείται. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Η υπογραφή όπως λήφθηκε. |

### Τιμή Επιστροφής

Αληθής εάν η υπογραφή είναι έγκυρη, ψευδής διαφορετικά.

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [DSACryptoServiceProvider](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)