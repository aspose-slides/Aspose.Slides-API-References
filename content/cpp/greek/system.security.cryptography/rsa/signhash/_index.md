---
title: SignHash()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: Υπολογίζει την υπογραφή για την καθορισμένη τιμή hash.
type: docs
weight: 144
url: /el/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) μέθοδος

Υπολογίζει την υπογραφή για την καθορισμένη τιμή hash.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Επιχειρήματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Τιμή hash. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Αλγόριθμος hash. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Λειτουργία επένδυσης. επιστρέφει [RSA](../) υπογραφή για την καθορισμένη hash. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [RSASignaturePadding](../../rsasignaturepadding/)
* Κλάση [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)