---
title: HashData()
second_title: Αναφορά API του Aspose.Slides για C++
description: Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού.
type: docs
weight: 105
url: /el/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) για κατακερματισμό. |
| offset | **int32_t** | Μετατόπιση στο **data**. |
| count | **int32_t** | Αριθμός byte για κατακερματισμό. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Αλγόριθμος κατακερματισμού. |

### Τιμή Επιστροφής

Κατακερματισμένα δεδομένα.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου δυαδικού ρεύματος χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | Δυαδικό ρεύμα προς κατακερματισμό. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | Αλγόριθμος κατακερματισμού. |

### Τιμή Επιστροφής

Κατακερματισμένα δεδομένα.

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)