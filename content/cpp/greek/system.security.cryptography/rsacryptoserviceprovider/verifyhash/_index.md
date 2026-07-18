---
title: VerifyHash()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ελέγχει την υπογραφή των δεδομένων.
type: docs
weight: 222
url: /el/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method


Ελέγχει την υπογραφή των δεδομένων.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Κατακερματισμός που υπολογίστηκε για τα ληφθέντα δεδομένα. |
| str | const [String](../../../system/string/)\& | Όνομα του χρησιμοποιημένου αλγόριθμου κατακερματισμού. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογραφή όπως ελήφθη. |

### Τιμή Επιστροφής

Αληθές αν η υπογραφή είναι έγκυρη, ψευδές διαφορετικά.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method


Επιβεβαιώνει ότι η υπογραφή του συγκεκριμένου κατακερματισμού είναι έγκυρη.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | Τιμή κατακερματισμού των υπογεγραμμένων δεδομένων. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | Λειτουργία συμπλήρωσης. επιστρέφει αληθές αν η υπογραφή είναι έγκυρη, διαφορετικά - ψευδές. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [RSACryptoServiceProvider](../)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)