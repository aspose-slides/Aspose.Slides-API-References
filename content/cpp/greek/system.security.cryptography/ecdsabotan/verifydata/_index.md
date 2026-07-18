---
title: VerifyData()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιβεβαιώνει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.
type: docs
weight: 170
url: /el/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method

Επιβεβαιώνει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. Επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) method

Επιβεβαιώνει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| offset | **int32_t** | Μετατόπιση στα **data**. |
| count | **int32_t** | Αριθμός byte για κατακερματισμό. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. Επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) method

Επιβεβαιώνει ότι η υπογραφή της συγκεκριμένης δυαδικής ροής είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. Επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Επιβεβαιώνει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. Επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Επιβεβαιώνει ότι η υπογραφή των συγκεκριμένων δεδομένων είναι έγκυρη.

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
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. Επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

Επιβεβαιώνει ότι η υπογραφή της συγκεκριμένης δυαδικής ροής είναι έγκυρη.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. Επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## Δείτε επίσης

* Τύπος [ByteArrayPtr](../../../system/bytearrayptr/)
* Τύπος [StreamPtr](../../../system/streamptr/)
* Κλάση [ECDsaBotan](../)
* Δομή [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)