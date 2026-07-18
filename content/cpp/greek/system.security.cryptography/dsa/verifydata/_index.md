---
title: VerifyData()
second_title: Αναφορά API Aspose.Slides για C++
description: Επαληθεύει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.
type: docs
weight: 92
url: /el/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Επαληθεύει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει true εάν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Επαληθεύει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| offset | **int32_t** | Μετατόπιση στα **data**. |
| count | **int32_t** | Αριθμός bytes για κατακερματισμό. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει true εάν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Επαληθεύει ότι η υπογραφή του συγκεκριμένου δυαδικού ρεύματος είναι έγκυρη.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει true εάν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)