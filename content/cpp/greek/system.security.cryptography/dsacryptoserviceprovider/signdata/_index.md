---
title: SignData()
second_title: Aspose.Slides για C++ API Αναφορά
description: Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.
type: docs
weight: 183
url: /el/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) μέθοδος

Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) για ανάγνωση των δεδομένων εισόδου από. |

### Τιμή επιστροφής

[DSA](../../dsa/) υπογραφή για τα καθορισμένα δεδομένα.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) μέθοδος

Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Ροή για ανάγνωση των δεδομένων που υπογράφονται. |

### Τιμή επιστροφής

[DSA](../../dsa/) υπογραφή για τα καθορισμένα δεδομένα.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) μέθοδος

Υπολογίζει την υπογραφή της καθορισμένης τιμής εισόδου.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) για ανάγνωση των δεδομένων εισόδου από. |
| offset | **int32_t** | Αρχικό δείκτη του τμήματος του buffer εισόδου. |
| count | **int32_t** | Μέγεθος τμήματος του buffer εισόδου. |

### Τιμή επιστροφής

[DSA](../../dsa/) υπογραφή για τα καθορισμένα δεδομένα.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) μέθοδος

Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει [DSA](../../dsa/) υπογραφή για τα δεδομένα εισόδου. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) μέθοδος

Υπολογίζει την τιμή κατακερματισμού του καθορισμένου πίνακα δεδομένων χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Πίνακας δεδομένων εισόδου. |
| offset | **int32_t** | Μετατόπιση στο **data**. |
| count | **int32_t** | Αριθμός byte που θα χρησιμοποιηθούν ως δεδομένα εισόδου. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει [DSA](../../dsa/) υπογραφή για τα δεδομένα εισόδου. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) μέθοδος

Υπολογίζει την τιμή κατακερματισμού του καθορισμένου δυαδικού ρεύματος χρησιμοποιώντας τον καθορισμένο αλγόριθμο κατακερματισμού και υπογράφει το αποτέλεσμα.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Δυαδική ροή. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. επιστρέφει [DSA](../../dsa/) υπογραφή για τα δεδομένα εισόδου. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Κλάση [DSACryptoServiceProvider](../)
* Κλάση [Stream](../../../system.io/stream/)
* Δομή [HashAlgorithmName](../../hashalgorithmname/)
* Ονοματικόχώρο [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)