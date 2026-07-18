---
title: VerifyData()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Επαληθεύει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.
type: docs
weight: 105
url: /el/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Επαληθεύει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. return true if signature is valid, otherwise - false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Επαληθεύει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| offset | **int32_t** | Μετατόπιση στα **data**. |
| count | **int32_t** | Αριθμός byte για κατακερματισμό. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. return true if signature is valid, otherwise - false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Επαληθεύει ότι η υπογραφή του συγκεκριμένου δυαδικού ρεύματος είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. return true if signature is valid, otherwise - false. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Κλάση [ECDsa](../)
* Δομή [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)