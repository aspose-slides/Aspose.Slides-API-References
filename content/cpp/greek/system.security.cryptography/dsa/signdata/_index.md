---
title: SignData()
second_title: Aspose.Slides για C++ Αναφορά API
description: Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.
type: docs
weight: 79
url: /el/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράπτει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. Επιστρέφει την υπογραφή [DSA](../) για τα δεδομένα εισόδου. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) μέθοδος

Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράπτει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. |
| offset | **int32_t** | Μετατόπιση στα **data**. |
| count | **int32_t** | Αριθμός bytes που θα χρησιμοποιηθούν ως δεδομένα εισόδου. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. Επιστρέφει την υπογραφή [DSA](../) για τα δεδομένα εισόδου. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) μέθοδος

Υπολογίζει την τιμή κατακερματισμού της καθορισμένης δυαδικής ροής χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Δυαδική ροή. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. Επιστρέφει την υπογραφή [DSA](../) για τα δεδομένα εισόδου. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Κλάση [DSA](../)
* Δομή [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)