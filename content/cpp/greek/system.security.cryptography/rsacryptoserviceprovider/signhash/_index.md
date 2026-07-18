---
title: SignHash()
second_title: Aspose.Slides για C++ API Αναφορά
description: Υπολογίζει την υπογραφή για την καθορισμένη τιμή κατακερματισμού.
type: docs
weight: 196
url: /el/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) μέθοδος

Υπολογίζει την υπογραφή για την καθορισμένη τιμή κατακερματισμού.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Τιμή κατακερματισμού. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Αλγόριθμος κατακερματισμού. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Λειτουργία ανάπληξης. επιστρέφει [RSA](../../rsa/) υπογραφή για τον καθορισμένο κατακερματισμό. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) μέθοδος

Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου. Δεν είναι υλοποιημένο.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Τιμή κατακερματισμού των δεδομένων που θα υπογραφούν. |
| str | const [String](../../../system/string/)\& | Αναγνωριστικό αλγορίθμου κατακερματισμού που χρησιμοποιείται για τη δημιουργία του κατακερματισμού. |

### Τιμή Επιστροφής

[RSA](../../rsa/) υπογραφή για τα καθορισμένα δεδομένα.

## Δείτε επίσης

* Τύπος [ByteArrayPtr](../../../system/bytearrayptr/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [RSASignaturePadding](../../rsasignaturepadding/)
* Κλάση [RSACryptoServiceProvider](../)
* Κλάση [String](../../../system/string/)
* Δομή [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)