---
title: VerifyData()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιβεβαιώνει ότι η υπογραφή των καθορισμένων δεδομένων είναι έγκυρη.
type: docs
weight: 157
url: /el/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method

Επιβεβαιώνει ότι η υπογραφή των καθορισμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Λειτουργία γεμίσματος. επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method

Επιβεβαιώνει ότι η υπογραφή των καθορισμένων δεδομένων είναι έγκυρη.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Υπογεγραμμένα δεδομένα. |
| offset | **int32_t** | Μετατόπιση στα **data**. |
| count | **int32_t** | Αριθμός bytes για κατακερματισμό. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Λειτουργία γεμίσματος. επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) method

Επιβεβαιώνει ότι η υπογραφή του καθορισμένου δυαδικού ρεύματος είναι έγκυρη.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | Υπογεγραμμένα δεδομένα. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Δεδομένα υπογραφής. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | Αλγόριθμος κατακερματισμού. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | Λειτουργία γεμίσματος. επιστρέφει true αν η υπογραφή είναι έγκυρη, διαφορετικά - false. |

## Δείτε επίσης

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Κλάση [RSASignaturePadding](../../rsasignaturepadding/)
* Κλάση [RSA](../)
* Δομή [HashAlgorithmName](../../hashalgorithmname/)
* Χώρος ονομάτων [System::Security::Cryptography](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)