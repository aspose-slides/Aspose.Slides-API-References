---
title: VerifySignature()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Επαληθεύει την υπογραφή DSA για τα καθορισμένα δεδομένα.
type: docs
weight: 118
url: /el/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) μέθοδος

Επαληθεύει την υπογραφή [DSA](../../dsa/) για τα καθορισμένα δεδομένα.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) υπογεγραμμένο με **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) υπογραφή. |

### Τιμή Επιστροφής

true - εάν **rgb_signature** ταυτίζεται με την υπογραφή [DSA](../../dsa/) που υπολογίζεται στο **rgb_hash**, διαφορετικά - false.

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Κλάση [DSACryptoServiceProvider](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)