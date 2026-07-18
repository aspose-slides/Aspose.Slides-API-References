---
title: VerifyData()
second_title: Αναφορά API του Aspose.Slides για C++
description: Ελέγχει την υπογραφή των δεδομένων.
type: docs
weight: 209
url: /el/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method


Έλεγχος υπογραφής δεδομένων.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) για έλεγχο υπογραφής. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Η υπογραφή όπως λήφθηκε. |

### Τιμή Επιστροφής

Αληθές εάν η υπογραφή είναι έγκυρη, ψευδές διαφορετικά.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Επαληθεύει ότι η υπογραφή των καθορισμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερδισμού. επιστρέφει αληθές εάν η υπογραφή είναι έγκυρη, διαφορετικά - ψευδές. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Επαληθεύει ότι η υπογραφή των καθορισμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| offset | **int32_t** | Μετατόπιση στα **data**. |
| count | **int32_t** | Αριθμός byte για κατακερδισμό. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερδισμού. επιστρέφει αληθές εάν η υπογραφή είναι έγκυρη, διαφορετικά - ψευδές. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method


Επαληθεύει ότι η υπογραφή της καθορισμένης δυαδικής ροής είναι έγκυρη.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερδισμού. επιστρέφει αληθές εάν η υπογραφή είναι έγκυρη, διαφορετικά - ψευδές. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Κλάση [DSACryptoServiceProvider](../)
* Δομή [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)