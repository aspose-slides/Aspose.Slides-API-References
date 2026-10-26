---
title: SignData()
second_title: Aspose.Slides για C++ Αναφορά API
description: Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων και υπογράφει το αποτέλεσμα.
type: docs
weight: 131
url: /el/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων και υπογράφει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. επιστρέφει την υπογραφή ECDSA για τα δεδομένα εισόδου. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων και υπογράφει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. |
| offset | **int32_t** | Μετατόπιση στο **data**. |
| count | **int32_t** | Αριθμός byte που θα χρησιμοποιηθούν ως δεδομένα εισόδου. επιστρέφει την υπογραφή ECDSA για τα δεδομένα εισόδου. |

## ECDsaBotan::SignData(const StreamPtr\&) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου δυαδικού ρεύματος και υπογράφει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Δυαδική ροή. επιστρέφει την υπογραφή ECDSA για τα δεδομένα εισόδου. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει την υπογραφή ECDSA για τα δεδομένα εισόδου. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. |
| offset | **int32_t** | Μετατόπιση στο **data**. |
| count | **int32_t** | Αριθμός byte που θα χρησιμοποιηθούν ως δεδομένα εισόδου. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει την υπογραφή ECDSA για τα δεδομένα εισόδου. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) μέθοδος


Υπολογίζει την τιμή κατακερματισμού του καθορισμένου δυαδικού ρεύματος χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Δυαδική ροή. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει την υπογραφή ECDSA για τα δεδομένα εισόδου. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)