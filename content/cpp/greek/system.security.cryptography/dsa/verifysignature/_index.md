---
title: VerifySignature()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επαληθεύει την υπογραφή DSA για τα καθορισμένα δεδομένα.
type: docs
weight: 14
url: /el/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) μέθοδος

Επαληθεύστε την υπογραφή [DSA](../) για τα καθορισμένα δεδομένα.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) υπογεγραμμένο με **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) υπογραφή. |

### Τιμή επιστροφής

true - εάν **rgb_signature** ταιριάζει με την [DSA](../) υπογραφή που υπολογίστηκε στο **rgb_hash**, διαφορετικά - false.

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Κλάση [DSA](../)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)