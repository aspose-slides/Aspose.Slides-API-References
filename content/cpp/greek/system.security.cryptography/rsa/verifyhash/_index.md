---
title: VerifyHash()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επαληθεύει ότι η υπογραφή του καθορισμένου κατακερματισμού είναι έγκυρη.
type: docs
weight: 170
url: /el/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method

Επαληθεύει ότι η υπογραφή του καθορισμένου κατακερματισμού είναι έγκυρη.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Τιμή κατακερματισμού των υπογεγραμμένων δεδομένων. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Λειτουργία γεμίσματος. επιστρέφει true εάν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [RSASignaturePadding](../../rsasignaturepadding/)
* Κλάση [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)